# Synthesi 

![sqlutions logo](https://github.com/user-attachments/assets/4884e8b3-b59a-45ba-ad13-13faa8d4d9b3)

### Bem-vindo ao repositório do nosso projeto Synthesi, desenvolvido pela equipe _**SQLutions**_ do curso Banco de Dados 5º Semestre da Fatec de São José dos Campos.

---

<div align="center">

[Sobre o Projeto](#-sobre-o-projeto) | [Backlogs e User Stories](#-backlogs--user-stories) | [Tecnologias](#%EF%B8%8F-tecnologias) | [Equipe](#-equipe)

</div>

## 📑 Desafio
---

O cliente relatou que possuía uma grande quantidade de dados referentes a projetos de programas, estes dados estavam dispersos entre sistemas e bancos de dados, tornando difícil a analise e vista geral dos projetos, nos foi proposto então a construção de um ambiente analítico que iria tanto juntar estes dados, quanto transforma-los em informações uteis para tomada de decisões dos gestores de projetos.

## Solução (Synthesi)
---
Decidimos então construir uma aplicação web para centralizar, transformar e organizar todos os dados destes projetos utilizando estratégias de Data Warehouse.

### 🏁 Entregas de Sprints

| Sprint | Previsão                | Status       | Histórico    |
| ------ | ----------------------- | ------------ | ------------ |
| 01     | 08/09/2025 a 28/09/2025 | Etapa atual  | Em andamento |
| 02     | 06/10/2025 a 26/10/2025 | Etapa futura | Etapa Futura |
| 03     | 03/11/2025 a 23/11/2025 | Etapa futura | Etapa Futura |

[→ Voltar ao topo](#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 🎯 Backlogs & User Stories

### ✅ Requisitos Funcionais

|  ID   |            Funcionalidade             | Descrição                                                                                                                                                            | Prioridade |
| :---: | :-----------------------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------: |
| RF-1  |  Importação e normalização de Dados   | Permitir que dados possam ser importados a partir de arquivos csv e sejam convertidos para dimensões e fatos do banco.                                               |    Alta    |
| RF-2  |     Processamento de Horas Totais     | Deve calcular horas totais trabalhadas de um projeto.                                                                                                                |    Alta    |
| RF-3  |   Painel de projetos centralizados    | Lista todos os projetos e programas cadastrados em uma unica tela                                                                                                    |    Alta    |
| RF-4  |        Filtragem por Programa         | O sistema deve permitir que os dados de cada tela possam ser filtrados por programas além de apenas um projeto.                                                      |   Média    |
| RF-5  |           Busca de projetos           | O sistema Possui um campo de pesquisa para localizar e pesquisar projetos                                                                                            |    Alta    |
| RF-6  |        Custo total por projeto        | O sistema deve calcular o valor de todos os materiais empenhados em um projeto e demonstra-lo junto com horas totais trabalhadas                                     |    Alta    |
| RF-7  |  Visualização de Pipeline de compra   | A aplicação deve exibir informações sobre o fluxo de materiais pedidos e recebidos                                                                                   |    Alta    |
| RF-8  |     Alerta de entregas atrasadas      | O sistema deve conter informações de materiais que ultrapassaram a previsão de entrega e não foram recebidas                                                         |    Alta    |
| RF-9  |     Gestão de estoque de projeto      | A aplicação precisa exibir informações da quantidade de materiais no estoque                                                                                         |   Media    |
| RF-10 |         Monitorar prioridades         | O sistema deve possuir um filtro de pedidos de prioridade "Urgente" ou "Alta" não entregues.                                                                         |   Baixa    |
| RF-11 |      Lista de status de tarefas       | A aplicação deve possuir uma exibição das tarefas de cada projeto                                                                                                    |   Baixa    |
| RF-12 |     Indicadores de produtividade      | O sistema deve monitorar os engenheiros e disponibilizar uma porcentagem de produtividade comparando horas estimadas com horas trabalhadas para finalizar uma tarefa |   Baixa    |
| RF-13 |         Dados de fornecedores         | A aplicação deve fornecer dados dos fornecedores, como tempo de entrega, histórico de atraso frequente e preço                                                       |   Media    |
| RF-14 | Importação de dados feita pelo gestor | O sistema deve permitir o gestor importar arquivos .csv para novos projetos                                                                                          |   Media    |


---



### 📌 Backlog do Produto
---

| Rank | Priodidade | User Story                                                                                                                                                                                                                  | Estimativa | Sprint | Requisitos            |
| ---- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------ | --------------------- |
| 1    | Alta       | US-1 - Como gestor quero ver os gastos totais com o projeto (Gastos com materiais e horas trabalhadas), para economizar tempo pesquisando e calculando os custos de cada projeto                                        | 13         | 1      | RF-2<br>RF-6          |
| 2    | Alta       | US-2 - Como gestor gostaria de ver dados de compras (Solicitação, pedido, recebimento) referentes a cada projeto, para economizar tempo em descobrir materiais atrasados e valores gastos                               | 13         | 1      | RF-7<br>RF-8<br>RF-10 |
| 3    | Alta       | US-7 - Como gestor gostaria de uma pagina que mostrasse todos os programas e projetos centralizados podendo filtrar por programa e pesquisar um determinado projeto, para economizar tempo ao tentar navegar o programa | 3          | 2      | RF-3<br>RF-4<br>RF-5  |
| 4    | Alta       | US-3 - Como gestor quero ver dados do estoque de materiais de cada projeto, para economizar tempo e esforço na hora de checar o estoque de materiais comprados e se há registros inconsistentes (Materiais faltando)    | 13*        | 2      | RF-9                  |
| 5    | Media      | US-4 - Como gestor gostaria de ver dados de fornecedores, para ajudar no planejamento de tempo de espera para chegar do material e economizar e dinheiro escolhendo um fornecedor confiável com valores mais baixos.    | 13*        | 2      | RF-13                 |
| 6    | Media      | US-6 - Como gestor gostaria de importar dados de planilhas CSV sobre projetos novos, para economizar tempo e esforço da equipe ao inserir estes dados                                                                   | 5*         |        | RF-1<br>RF-14         |
| 7    | Baixa      | US-5 - Como gestor gostaria de ver o estado das tarefas do projeto, afim de entender o estado e andamento de cada projeto facilmente, economizando tempo pesquisando e consultando outros colaboradores                 | 8*         | 3      | RF-11<br>RF-12        |



---

### 📌 Backlog das Sprints

---

### 1️⃣ Sprint 1

## 🎯 Metas da Sprint
| Capacidade estimada da equipe por sprint | 30                                                  |
| ---------------------------------------- | --------------------------------------------------- |
| Meta da sprint                           | User Stories: US-1 e US-2 (26 Story Points) |
| Previsão da Sprint (extras)              | US-7 (3 Story Points)                           |

---

## Backlog

| Rank  | Priodidade                | User Story                                                                                                                                                                                             | Estimativa | Sprint | Requisitos            |
| ----- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ------ | --------------------- |
| **1** | **Alta** <br>(**_META_**) | **US-1 - Como gestor quero ver os gastos totais com o projeto (Gastos com materiais e horas trabalhadas), para economizar tempo pesquisando e calculando os custos de cada projeto ** (**_META_**) | 13         | **1**  | RF-2<br>RF-6          |
| 2     | Alta                      | US-2 - Como gestor gostaria de ver dados de compras (Solicitação, pedido, recebimento) referentes a cada projeto, para economizar tempo em descobrir materiais atrasados e valores gastos          | 13         | 1      | RF-7<br>RF-8<br>RF-10 |




---

### 2️⃣ Sprint 2

## 🎯 Metas da Sprint 2
| Capacidade estimada da equipe por sprint | 30                                                  |
| ---------------------------------------- | --------------------------------------------------- |
| Meta da sprint                           | User Stories: US-3 e US-4 (19 Story Points) |
| Previsão da Sprint (extras)              | User Story 5 (5 Story Points)                       |

---
## Backlog
| Rank  | Prioridade           | User Story                                                                                                                                                                                                                             | Estimativa | Sprint | Requisitos           |
| ----- | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ | -------------------- |
| **3** | **Alta (_META_)**    | **US-7 - Como gestor gostaria de uma pagina que mostrasse todos os programas e projetos centralizados podendo filtrar por programa e pesquisar um determinado projeto, para economizar tempo ao tentar navegar o programa (META)** | **3**        | **2**  | RF-3<br>RF-4<br>RF-5 |
| **3** | **Alto<br>(_META_)** | **US-3 - Como gestor quero ver dados do estoque de materiais de cada projeto, para economizar tempo e esforço na hora de checar o estoque para compras de materiais e se há falta de materiais (_META_)**                          | **13***      | **2**  | RF-9                 |
| 4     | Media                | US-4 - Como gestor gostaria de ver dados de fornecedores, para ajudar no planejamento de tempo de espera para chegar do material e economizar tempo e dinheiro escolhendo um fornecedor que vende por um valor mais baixo.         | 13*          | 2      | RF-13                |

---

### 3️⃣ Sprint 3

## 🎯 Metas da Sprint 3
| Capacidade estimada da equipe por sprint | 30                                                  |
| ---------------------------------------- | --------------------------------------------------- |
| Meta da sprint                           | User Stories: US-8 e US-5 (13 Story Points) |
| Previsão da Sprint (extras)              |                                                     |

---
## Backlog
| Rank  | Prioridade         | User Story                                                                                                                                                                                                               | Estimativa | Sprint | Requisitos     |
| ----- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | ------ | -------------- |
| **5** | **Media (_META_)** | **US-8 - Como gestor gostaria de importar dados de planilhas CSV sobre projetos novos, para economizar tempo e esforço da equipe ao inserir estes dados**                                                            | **5***       | **3**  | RF-1<br>RF-14  |
| 6     | Baixa<br>          | US-5 - Como gestor gostaria de ver o estado das tarefas do projeto, afim de entender o estado e andamento de cada projeto facilmente, economizando tempo pesquisando e consultando outros colaboradores (**_META_**) | 8*           | 3      | RF-11<br>RF-12 |

[→ Voltar ao topo](#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 🛠️ Tecnologias

As seguintes ferramentas, linguagens, bibliotecas e tecnologias que foram usadas na construção do projeto:

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario) 
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://slack.com/) 
[![Figma](https://img.shields.io/badge/Figma-0ACF83?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/)
[![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://github.com/eslint/eslint)

### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/) 
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/) 

### Frontend

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)


[→ Voltar ao topo](https://github.com/SQLutions-FATEC/API-3-Semestre/blob/main/README.md#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 👥 Equipe

|                                                                                                         | Função        | Nome                         | Redes                                                                                                                                                                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------- | ------------- | ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![bryan](https://github.com/user-attachments/assets/de3c76c1-183c-4e13-8856-7dd87834be2b)               | Product Owner | Bryan Matheus                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bryan-matheus-5aa0a3302)         [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BryanARMatheus)      |
| ![daniel](https://github.com/user-attachments/assets/6cb4f0c1-0bef-43ff-8e57-e633f145dbdf)              | Scrum Master  | Daniel Sendreti Broder       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielbroder)                    [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/d-broder)            |
| ![gloria](https://github.com/user-attachments/assets/2de16de0-fd28-4700-b5b5-a00702dfce10)              | Desenvolvedor | Glória Brito                 | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gloriafbrito/)                   [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GloBrito)            |
| ![caina](https://github.com/user-attachments/assets/a6f52b8c-11c7-4f20-9647-004cd04c60bc)               | Desenvolvedor | Cainã Nascimento Melo        | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cain%C3%A3-melo/)                [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CainaNascimentoMelo) |
| ![enzo](https://github.com/user-attachments/assets/f228df2a-1bae-408d-9d39-d5808bea56bc)                | Desenvolvedor | Enzo Lemos Franco            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-lemos-franco-002651293/)  <br>[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnzoLFranco)       |
| ![gabriel vasconcelos](https://github.com/user-attachments/assets/0ac1090d-15b5-44a9-b68c-79e890a1783d) | Desenvolvedor | Gabriel Vasconcelos Ferreira | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-vasconcelos-255979262)<br>[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabrielvascf)       |
| ![gabriel carvalho](https://github.com/user-attachments/assets/20a93e32-fdf9-4bbe-b798-08a1985c5db6)    | Desenvolvedor | Gabriel Carvalho Silva       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-carvalho-87569336a)      [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gabriecarvalho)      |


[→ Voltar ao topo](https://github.com/SQLutions-FATEC/API-3-Semestre/blob/main/README.md#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)
