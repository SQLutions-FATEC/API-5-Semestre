# Synthesi 

![sqlutions logo](https://github.com/user-attachments/assets/4884e8b3-b59a-45ba-ad13-13faa8d4d9b3)

### Welcome to the repository of project Synthesi, developed by team **_SQLutions_** for the 5th Semester Database course at FATEC São José dos Campos.

---

<div align="center">

[The Challenge(#-the-challenge) | [Backlogs and User Stories](#-backlogs--user-stories) | [Thechnologies](#%EF%B8%8F-technologies) | [Team](#-team)

</div>

## 📑 The Challenge

---

The client reported that a large amount of data regarding program projects. this data was scattered across various systems and databases, making analysis and overall project oversight difficult. We were proposed to build an analytical environment that would both unify this data and transform it into useful information for project managers' decision-making.

## The Solution (Synthesi)

---

We decided to build a web application to centralize, transform, and organize all project data using Data Warehouse strategies.

### 🏁 Sprint Deliverables

|Sprint|Forecast|Status|History|
|---|---|---|---|
|01|03/16/2025 to 04/05/2025|Current Stage|In Progress|
|02|04/23/2025 to 05/03/2025|Future Stage|Future Stage|
|03|05/11/2025 to 05/31/2025|Future Stage|Future Stage|

[→ Back to top](https://www.google.com/search?q=%23synthesi)

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

|Rank|Priority|User Story|Estimate|Sprint|Requirements|
|---|---|---|---|---|---|
|1|High|US-1 - As a manager, I want to see the total project costs (material expenses and hours worked) to save time researching and calculating costs for each project.|13|1|RF-2<br><br>  <br><br>RF-6|
|2|High|US-2 - As a manager, I would like to see purchasing data (request, order, receipt) for each project to save time in identifying late materials and amounts spent.|13|1|RF-7<br><br>  <br><br>RF-8<br><br>  <br><br>RF-10|
|3|High|US-7 - As a manager, I would like a page that displays all centralized programs and projects, allowing filtering by program and searching for a specific project to save time when navigating the program.|3|2|RF-3<br><br>  <br><br>RF-4<br><br>  <br><br>RF-5|
|4|High|US-3 - As a manager, I want to see the material inventory data for each project to save time and effort when checking the stock for purchased materials and if there are inconsistent records (missing materials).|13*|2|RF-9|
|5|Medium|US-4 - As a manager, I would like to see supplier data to help plan lead times and save time and money by choosing a reliable supplier with lower prices.|13*|2|RF-13|
|6|Medium|US-6 - As a manager, I would like to import data from CSV spreadsheets about new projects to save time and team effort when entering this data.|5*||RF-1<br><br>  <br><br>RF-14|
|7|Low|US-5 - As a manager, I would like to see the status of project tasks to easily understand the state and progress of each project, saving time spent researching and consulting other team members.|8*|3|RF-11<br><br>  <br><br>RF-12|

---

### 📌 Sprint Backlog

---

### 1️⃣ Sprint 1

## 🎯 Sprint Goals

|Estimated team capacity per sprint|30|
|---|---|
|Sprint Goal|User Stories: US-1 and US-2 (26 Story Points)|
|Sprint Forecast (extras)|US-7 (3 Story Points)|

---

## Backlog

|Rank|Priority|User Story|Estimate|Sprint|Requirements|
|---|---|---|---|---|---|
|**1**|**High**<br><br>  <br><br>(**_GOAL_**)|**US-1 - As a manager, I want to see total project costs (material expenses and hours worked) to save time researching and calculating costs for each project.** (**_GOAL_**)|13|**1**|RF-2<br><br>  <br><br>RF-6|
|2|High|US-2 - As a manager, I would like to see purchasing data (request, order, receipt) for each project to save time in identifying late materials and amounts spent.|13|1|RF-7<br><br>  <br><br>RF-8<br><br>  <br><br>RF-10|

---

### 2️⃣ Sprint 2

## 🎯 Sprint 2 Goals

|Estimated team capacity per sprint|30|
|---|---|
|Sprint Goal|User Stories: US-3 and US-4 (19 Story Points)|
|Sprint Forecast (extras)|User Story 5 (5 Story Points)|

---

## Backlog

|Rank|Priority|User Story|Estimate|Sprint|Requirements|
|---|---|---|---|---|---|
|**3**|**High (_GOAL_)**|**US-7 - As a manager, I would like a page that displays all centralized programs and projects, allowing filtering by program and searching for a specific project to save time when navigating the program (GOAL).**|**3**|**2**|RF-3<br><br>  <br><br>RF-4<br><br>  <br><br>RF-5|
|**3**|High<br><br>  <br><br>(_GOAL_)|**US-3 - As a manager, I want to see the material inventory data for each project to save time and effort when checking the stock for material purchases and if there is a shortage of materials (_GOAL_).**|**13***|**2**|RF-9|
|4|Medium|US-4 - As a manager, I would like to see supplier data to help plan lead times and save time and money by choosing a supplier that sells at a lower price.|13*|2|RF-13|

---

### 3️⃣ Sprint 3

## 🎯 Sprint 3 Goals

|Estimated team capacity per sprint|30|
|---|---|
|Sprint Goal|User Stories: US-8 and US-5 (13 Story Points)|
|Sprint Forecast (extras)||

---

## Backlog

|Rank|Priority|User Story|Estimate|Sprint|Requirements|
|---|---|---|---|---|---|
|**5**|**Medium (_GOAL_)**|**US-8 - As a manager, I would like to import data from CSV spreadsheets about new projects to save time and team effort when entering this data.**|**5***|**3**|RF-1<br><br>  <br><br>RF-14|
|6|Low|US-5 - As a manager, I would like to see the status of project tasks to easily understand the state and progress of each project, saving time spent researching and consulting other team members (**_GOAL_**).|8*|3|RF-11<br><br>  <br><br>RF-12|

[→ Back to top](https://www.google.com/search?q=%23synthesi)

## 🛠️ Technologies

The following tools, languages, libraries, and technologies were used in the project's construction:

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


[→ Back to top](https://www.google.com/search?q=%23synthesi)

## 👥 Team

| Photo                                                                                                   | Function      | Name                         | Socials                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------- | ------------- | ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![bryan](https://github.com/user-attachments/assets/de3c76c1-183c-4e13-8856-7dd87834be2b)               | Product Owner | Bryan Matheus                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bryan-matheus-5aa0a3302)         [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BryanARMatheus)      |
| ![daniel](https://github.com/user-attachments/assets/6cb4f0c1-0bef-43ff-8e57-e633f145dbdf)              | Scrum Master  | Daniel Sendreti Broder       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielbroder)                    [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/d-broder)            |
| ![caina](https://github.com/user-attachments/assets/a6f52b8c-11c7-4f20-9647-004cd04c60bc)               | Developer     | Cainã Nascimento Melo        | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cain%C3%A3-melo/)                [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CainaNascimentoMelo) |
| ![enzo](https://github.com/user-attachments/assets/f228df2a-1bae-408d-9d39-d5808bea56bc)                | Developer     | Enzo Lemos Franco            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-lemos-franco-002651293/)  <br>[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnzoLFranco)       |
| ![elbert](https://github.com/user-attachments/assets/a8f976c3-c1cb-4297-bdda-15ea4da1d94b)   | Developer     | Elbert Jean       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]()      [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]()      |
| ![gabriel vasconcelos](https://github.com/user-attachments/assets/0ac1090d-15b5-44a9-b68c-79e890a1783d) | Developer     | Gabriel Vasconcelos Ferreira | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-vasconcelos-255979262)<br>[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabrielvascf)       |
| ![gabriel carvalho](https://github.com/user-attachments/assets/20a93e32-fdf9-4bbe-b798-08a1985c5db6)    | Developer     | Gabriel Carvalho Silva       | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-carvalho-87569336a)      [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gabriecarvalho)      |
| ![gloria](https://github.com/user-attachments/assets/2de16de0-fd28-4700-b5b5-a00702dfce10)              | Developer     | Glória Brito                 | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gloriafbrito/)                   [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GloBrito)            |

[→ Back to top](https://www.google.com/search?q=%23synthesi)
