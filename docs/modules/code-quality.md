# Análise Estática Contínua e Qualidade de Código

Este documento detalha a integração do **SonarCloud** na arquitetura do projeto para o monitoramento contínuo de débitos técnicos, bugs e vulnerabilidades.

## Estrutura da Análise (Submódulos)
Como o projeto utiliza uma arquitetura baseada em submódulos, a análise de código ocorre de forma automatizada e isolada em cada repositório:
* **API-Backend:** Análise configurada com regras específicas para o ecossistema Python/Django.
* **API-Frontend:** Análise configurada com exclusões e regras voltadas para JS/TS e Next.js.

## Integração e Regras de Bloqueio
A integração com o SonarCloud foi projetada para atuar de maneira **informativa**. O status da qualidade do código é injetado diretamente nos Pull Requests (via *Pull Request Decoration*), oferecendo feedback rápido aos desenvolvedores.

**Nota operacional:** A aprovação do SonarCloud **não atua como bloqueio de merge**. Essa decisão garante que o time tenha total visibilidade sobre a introdução de novos bugs ou débitos técnicos, mas mantém a fluidez e a flexibilidade do fluxo de desenvolvimento.

## Automação e Periodicidade (GitHub Actions)
A comunicação entre os repositórios e o SonarCloud é gerenciada nativamente pelo GitHub Actions, através do workflow `build.yml`. As varreduras são disparadas nos seguintes cenários:

1. **Integração Contínua (Eventos em tempo real):** * A cada novo **Push** nas branches `main`, `develop-1`, `develop-2` e `develop-3`.
   * Na abertura, sincronização ou reabertura de **Pull Requests**.
2. **Varredura Completa (Agendada):**
   * Configuração de *schedule* (cron) executando a rotina de análise profunda em ambos os repositórios **toda sexta-feira às 23:00** (Horário de Brasília / UTC-3).
