# Wireframe
This file is based on all customer interactions and product Feature/Wireframe presentations.
Below are the wireframes and descriptions for each one:

## Sprint 1

### Overview
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/56b992f8-35ce-4fd3-8a0a-32b483656a70" />

The overview screen contains:
- Project header
- Project information (Name, Code, Manager, Estimated end date)
- Program information (Name, Code, Status, Responsible person, Start and end date)


- Important information cards
  - Hours worked
  - Estimated hours to finish the project (Based on remaining task hours)
  - Committed value in the project (Based on material commitment)
  - Total project expenditure (Sum of purchases, commitments, and hourly cost * hours worked)

- Commitment information
  - General commitment
    - Committed cost over time
    - Cost by material category
    - Total expenditure on the project
    - Table with all project commitments
   
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/71d3bf13-657e-4ba0-93d5-9e1a24505bcb" />

- Commitment by category (Filters by committed materials category)
  - Committed cost over time
  - Cost by different type of material within the same category
  - Total expenditure for that material
  - Table of materials in the category that were committed
   
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/233c1a9b-658d-44d8-a068-a0449735cb02" />

- Tasks
  - Burnup chart of hours worked on the project
  - Filter by task
  - Task information (Title, Responsible person, Most recent worker, last day worked)
  - Chart of employees who worked the most on the task
  - Total hours worked
  - Table with project tasks.

### Orders
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/20481664-2c90-4d3e-8eab-eb04e4f361ba" />

- Order tracking screen
  - Project delay history
  - Open or en-route high-priority orders
  - Quantity of open or en-route orders
  - Table with all project orders
 
## Sprint 2

### Requests

<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/a12d0ad0-b419-401c-b1ef-b933421f95a2" />

  - Approved requests for orders
  - Open high-priority requests and number of days since the product was requested
  - Quantity of open requests
  - Table with request information for specific queries


### Orders
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/840a516c-15b6-4d8e-909d-689b7e0eb775" />


- Chart showing the amount spent on orders and the expenditure date (only counts open, received, and partially received orders)
- Sum of total expenditure for all project orders
- Donut chart showing the material that spent the most money on orders (considering only open, received, and partially received orders)
- Table with the history of all orders and their monetary expenditures for more specific queries.

### Home
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/022199a7-137a-48f1-8cdd-00bfef738191" />

- Search bar for program names and codes
- Program dropdown on the project selection screen to ease navigation

<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/b48f3cc9-a1b3-4ba0-8e97-42ad1ef8a138" />

- Search bar for project names and codes.

### Estoque

<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/8f517ec1-24c4-45a9-b3b0-b571c602c522" />

- Information on materials "leftover from previous orders"; to avoid affecting other projects, we decided to create only a warning, which only appears for orders made within the same program, from projects that were canceled or suspended
- Information on open orders involving materials "leftover from previous orders"
- History of commitments for this project, for better inventory stock-out control
- Additional information on open orders using leftover materials, featuring the total value of "leftover" materials and the value currently being ordered for comparison
- And a donut chart to compare the monetary value of materials currently in stock

### Fornecedores
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/67baaec1-e0c2-4446-bbf2-4e981b31bf00" />

- Search by supplier name (corporate name), material category, city, program, and project.
- Clicking on one of the supplier cards will open a modal on the screen

<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/9c4781a7-0aa3-48e7-a89f-80d714a4f3b9" />

- All supplier information and analysis of previous orders and past delays.
- Consumer's previous orders with a project filter.

### Importação
<img width="90" height="90" alt="image" src="https://github.com/user-attachments/assets/b6ffe78f-215c-442a-9fe8-4e905e746397" />

- Clicking the button will open the user's file explorer to select a file; the program only accepts .csv files
- If the spreadsheet contains all the correct data, it will be imported and assimilated into the project database

# Login
<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/51ca83c9-fff7-4bfc-bddd-3be0232c9e7f" />

- User enters the data already registered in the system; the system verifies the data and allows the manager to access the project
- Each department can access specific screens relevant to their role,
- Button to view all project information in case the manager needs specific data regarding another department

<img width="640" height="580" alt="image" src="https://github.com/user-attachments/assets/5acccaec-1b35-4eec-9466-6a5394768401" />

- The manager can log out of the program and return to the initial login screen

Managers from different departments have access to these pages:

#### Finance

- Has access to the pages:
  - Overview (Can only see the commitment section)
  - Purchasing (Can only see the order expenses section)
  - Inventory
  - Suppliers

#### Purchasing

- Has access to the pages:
  - Purchasing

#### Warehouse

- Has access to the pages:
  - Inventory
  - Purchasing (Order tracking only)

#### Projects

- Has access to the pages:
  - Overview
  - Purchasing (Request and order tracking only)
