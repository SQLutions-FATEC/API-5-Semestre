# Análise Estática Contínua e Qualidade de Código

Este documento detalha a integração do **SonarCloud** na arquitetura do projeto para o monitoramento contínuo de débitos técnicos, bugs e vulnerabilidades.

## Estrutura da Análise (Submódulos)
Como o projeto utiliza uma arquitetura baseada em submódulos, a análise de código ocorre de forma automatizada e isolada em cada repositório:
* **API-Backend:** Análise configurada com regras específicas para o ecossistema Python/Django.
* **API-Frontend:** Análise configurada com exclusões e regras voltadas para JS/TS e React.

## Integração e Regras de Bloqueio
A integração com o SonarCloud foi projetada para atuar de maneira **informativa**. O status da qualidade do código é injetado diretamente nos Pull Requests (via *Pull Request Decoration*), oferecendo feedback rápido aos desenvolvedores.

**Nota operacional:** A aprovação do SonarCloud **não atua como bloqueio de merge**. Essa decisão garante que o time tenha total visibilidade sobre a introdução de novos bugs ou débitos técnicos, mas mantém a fluidez e a flexibilidade do fluxo de desenvolvimento.

## Automação e Periodicidade (GitHub Actions)
A comunicação entre os repositórios e o SonarCloud é gerenciada nativamente pelo GitHub Actions, através do workflow `build.yml`. As varreduras são disparadas nos seguintes cenários:

1. **Integração Contínua (Eventos em tempo real):** * A cada novo **Push** nas branches `main`, `develop-1`, `develop-2` e `develop-3`.
   * Na abertura, sincronização ou reabertura de **Pull Requests**.
2. **Varredura Completa (Agendada):**
   * Configuração de *schedule* (cron) executando a rotina de análise profunda em ambos os repositórios **toda sexta-feira às 23:00** (Horário de Brasília / UTC-3).

---

## Solução de Problemas Comuns (Troubleshooting)

Abaixo estão listados os problemas mais frequentes durante a execução da esteira de análise e suas respectivas soluções:

### 1. A Action falhou com erro de "Not authorized" ou "Token inválido"
* **Causa:** O repositório não tem acesso à credencial do SonarCloud.
* **Solução:** Verifique se a *Secret* `SONAR_TOKEN` foi criada corretamente nas configurações do repositório específico (`Settings > Secrets and variables > Actions`). O token deve ser o gerado pelo painel do SonarCloud para aquele projeto exato.

### 2. Alerta de Segurança no PR: "Use full commit SHA for this dependency"
* **Causa:** Ferramentas de segurança do GitHub (ou linters) alertam contra o uso de tags genéricas (como `@master`) em Actions de terceiros.
* **Solução:** Trata-se de um falso positivo para o nosso fluxo. A Action do SonarCloud exige o uso de tags de versão (como `@v2` ou `@v3`) para manter a compatibilidade com as atualizações do Node.js nos runners do GitHub. Mantenha a tag recomendada na documentação e marque o alerta como "Aceitar Risco" ou "Falso Positivo" no painel do SonarCloud.

### 3. A análise está demorando muito ou analisando arquivos de bibliotecas
* **Causa:** O SonarCloud está varrendo arquivos desnecessários (como pastas de build, bibliotecas ou ambientes virtuais), o que gera falsos positivos e lentidão.
* **Solução:** Verifique o arquivo `sonar-project.properties` na raiz do repositório. Confirme se a propriedade `sonar.exclusions` está configurada corretamente:
  * **No Frontend:** Deve ignorar `**/node_modules/**`, `build/**` e arquivos de teste.
  * **No Backend:** Deve ignorar `**/migrations/**`, `venv/**` e arquivos estáticos/HTML gerados pelo Django.

### 4. Os comentários do SonarCloud não aparecem no meu Pull Request
* **Causa:** O GitHub Actions não tem permissão para "escrever" o resultado no PR.
* **Solução:** Verifique se o arquivo `build.yml` contém a variável `GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}` injetada no ambiente (env) do passo do SonarCloud. Essa credencial nativa é obrigatória para a funcionalidade de *Pull Request Decoration*.
