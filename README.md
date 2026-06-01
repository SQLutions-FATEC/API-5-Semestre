# Synthesi 

![sqlutions logo](https://github.com/user-attachments/assets/4884e8b3-b59a-45ba-ad13-13faa8d4d9b3)

### Welcome to the repository of project Synthesi, developed by team **_SQLutions_** for the 5th Semester Database course at FATEC São José dos Campos.

---

<div align="center">

[The Challenge](#-the-challenge) | [Backlogs and User Stories](#-backlogs--user-stories) | [Technologies](#%EF%B8%8F-technologies) | [Team](#-team)

</div>

## 📑 The Challenge

---

The client reported that a large amount of data regarding program projects. this data was scattered across various systems and databases, making analysis and overall project oversight difficult. We were proposed to build an analytical environment that would both unify this data and transform it into useful information for project managers' decision-making.

## The Solution (Synthesi)

---

We decided to build a web application to centralize, transform, and organize all project data using Data Warehouse strategies.
Our project involves, a intuitive project and program selector, general view of the project with information about a variety of sectors, like materials used in the project, total cost and tasks.
We also offer a way to acompany any purchases or solicitations to purchase materials made towards the project.
Along with a page to see project inventory and if the stock meets demands of other material orders.


### 🏁 Sprint Deliverables

|Sprint|Forecast|Status|History|
|---|---|---|---|
|01|03/16/2025 to 04/05/2025|Completed Stage|Complete|
|02|04/23/2025 to 05/03/2025|Completed Stage|Complete|
|03|05/11/2025 to 05/31/2025|Future Stage|Planning|

[→ Back to top](#synthesi)

## 🎯 Backlogs & User Stories

### ✅ Functional Requirements

| ID    | Functionality                     | Description                                                                                                                                       | Priority |
| ----- | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| RF-1  | Data Import and Normalization     | Allow data to be imported from CSV files and converted into database dimensions and facts.                                                        | High     |
| RF-2  | Total Hours Processing            | Must calculate total hours worked on a project.                                                                                                   | High     |
| RF-3  | Centralized Projects Panel        | List all registered projects and programs on a single screen.                                                                                     | High     |
| RF-4  | Program Filtering                 | The system must allow data on each screen to be filtered by programs in addition to individual projects.                                          | Medium   |
| RF-5  | Project Search                    | The system must feature a search field to locate and search for projects.                                                                         | High     |
| RF-6  | Total Cost per Project            | The system must calculate the value of all materials committed to a project and display it alongside total hours worked.                          | High     |
| RF-7  | Purchasing Pipeline Visualization | The application must display information about the flow of ordered and received materials.                                                        | High     |
| RF-8  | Late Delivery Alerts              | The system must contain information about materials that have exceeded the delivery forecast and have not been received.                          | High     |
| RF-9  | Project Inventory Management      | The application needs to display information on the quantity of materials in stock.                                                               | Medium   |
| RF-10 | Priority Monitoring               | The system must have a filter for "Urgent" or "High" priority orders that have not been delivered.                                                | Low      |
| RF-11 | Task Status List                  | The application must have a display for each project's tasks.                                                                                     | Low      |
| RF-12 | Productivity Indicators           | The system must monitor engineers and provide a productivity percentage by comparing estimated hours with actual hours worked to complete a task. | Low      |
| RF-13 | Supplier Data                     | The application must provide supplier data, such as delivery time, frequent delay history, and price.                                             | Medium   |
| RF-14 | Data Import by Manager            | The system must allow the manager to import .csv files for new projects.                                                                          | Medium   |

---

### 📌 Product Backlog

---


| Rank | Priodidade | User Story                                                                                                                                                                                                                  | Estimativa | Sprint |
| ---- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------ |
| 1    | Alta       | [[US-1]] - Como gestor quero ver os gastos totais com o projeto (Gastos com materiais e horas trabalhadas), para economizar tempo pesquisando e calculando os custos de cada projeto                                        | 13         | 1      |
| 2    | Alta       | [[US-2]] - Como gestor gostaria de acompanhar o estado dos pedidos, para economizar tempo ao transformar solicitações em pedidos e apontar faltas de materiais em projetos                                                  | 8          | 1      |
| 3    | Alta       | [[US-7]] - Como gestor gostaria de uma pagina que mostrasse todos os programas e projetos centralizados podendo filtrar por programa e pesquisar um determinado projeto, para economizar tempo ao tentar navegar o programa | 5          | 2      |
| 4    | Alta       | [[US-8]] - Como gestor quero acompanhar solicitações feitas em cada projeto, para economizar tempo e esforço para entender a demanda de materiais para cada projeto                                                         | 5          | 2      |
| 5    | Alta       | [[US-9]] - Como gestor quero visualizar os gastos em pedidos feitos em cada projeto, para economizar tempo e esforço para entender os gastos em materiais de cada projeto                                                   | 5          | 2      |
| 6    | Alta       | [[US-3]] - Como gestor quero ver dados do estoque de materiais de cada projeto, para economizar tempo e esforço na hora de checar o estoque de materiais comprados e se há registros inconsistentes (Materiais faltando)    | 8          | 2      |
| 7    | Media      | [[US-4]] - Como gestor gostaria de ver dados de fornecedores, para ajudar no planejamento de tempo de espera para chegar do material e economizar e dinheiro escolhendo um fornecedor confiável com valores mais baixos.    | 8          | 3      |
| 8    | Media      | [[US-6]] - Como gestor gostaria de importar dados de planilhas CSV sobre projetos novos, para economizar tempo e esforço da equipe ao inserir estes dados                                                                   | 3          | 3      |
| 9    | Baixa      | [[US-10]] - Como gestor quero poder entrar no produto com minha conta de usuário, para receber apenas informações relevantes do meu setor sobre os projetos                                                                 | 5          | 3      |
| 10   | Baixa      | [[US-5]] - Como gestor gostaria de ver o estado das tarefas do projeto, afim de entender o estado e andamento de cada projeto facilmente, economizando tempo pesquisando e consultando outros colaboradores                 | 8          | 3      |

---

### 📌 Sprint Backlog

---

### [1️⃣ Sprint 1 - Backlog](/docs/project/Sprints/Sprint%201/Sprint_1.md)

---

### [2️⃣ Sprint 2 - Backlog](/docs/project/Sprints/Sprint%202/Sprint_2.md)


---

### [3️⃣ Sprint 3 - Backlog](/docs/project/Sprints/Sprint%203/Sprint_3.md)


[→ Back to top]((#synthesi))

## 🛠️ Technologies

The following tools, languages, libraries, and technologies were used in the project's construction:

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario) 
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://slack.com/) 
[![Figma](https://img.shields.io/badge/Figma-0ACF83?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/) 
[![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black)]
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://github.com/eslint/eslint)

### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/) 
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/) 

### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MaterialUI](https://img.shields.io/badge/Material%20UI-%23FFFFFF?style=for-the-badge&logo=MUI&logoColor=#007FFF)


[→ Back to top]((#synthesi))

## 👥 Team

| Photo                                                                                                   | Function      | Name                         | Socials                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------- | ------------- | ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![bryan](https://github.com/user-attachments/assets/de3c76c1-183c-4e13-8856-7dd87834be2b)               | Product Owner | Bryan Matheus                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bryan-matheus-5aa0a3302)         [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BryanARMatheus)      |
| ![daniel](https://github.com/user-attachments/assets/6cb4f0c1-0bef-43ff-8e57-e633f145dbdf)              | Scrum Master  | Daniel Sendreti Broder       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielbroder)                    [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/d-broder)            |
| ![caina](https://github.com/user-attachments/assets/a6f52b8c-11c7-4f20-9647-004cd04c60bc)               | Developer     | Cainã Nascimento Melo        | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cain%C3%A3-melo/)                [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CainaNascimentoMelo) |
| ![enzo](https://github.com/user-attachments/assets/f228df2a-1bae-408d-9d39-d5808bea56bc)                | Developer     | Enzo Lemos Franco            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-lemos-franco-002651293/)  <br>[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnzoLFranco)       |
| ![elbert](https://github.com/user-attachments/assets/a8f976c3-c1cb-4297-bdda-15ea4da1d94b)   | Developer     | Elbert Jean       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elbertjean)      [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ElbertJean)      |
| ![gabriel vasconcelos](https://github.com/user-attachments/assets/0ac1090d-15b5-44a9-b68c-79e890a1783d) | Developer     | Gabriel Vasconcelos Ferreira | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-vasconcelos-255979262)<br>[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabrielvascf)       |
| ![gabriel carvalho](https://github.com/user-attachments/assets/20a93e32-fdf9-4bbe-b798-08a1985c5db6)    | Developer     | Gabriel Carvalho Silva       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-carvalho-87569336a)      [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gabriecarvalho)      |
| ![gloria](https://github.com/user-attachments/assets/2de16de0-fd28-4700-b5b5-a00702dfce10)              | Developer     | Glória Brito                 | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gloriafbrito/)                   [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GloBrito)            |

[→ Back to top](#synthesi)
