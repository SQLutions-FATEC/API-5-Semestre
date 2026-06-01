## 1. Documentation and Modeling (Mandatory)

### 1.1 Dimensional Modeling: The dimensional data model must be formally documented and validated before the start of each sprint's implementation.

### 1.2 Database Artifacts: The documentation must obligatorily include the conceptual, logical, and physical models, as well as a detailed data dictionary (describing tables, fields, data types, constraints, keys, descriptions, and relationships).

### 1.3 API Documentation: The application programming interfaces must be documented.

## 2. Technologies and Architecture (Suggestions and Guidelines)

### 2.1 Programming Language: Python (Suggested by the partner).

### 2.2 Web Framework: Django (Suggested by the partner).

### 2.3 Data Architecture: The analytical environment must be structured using a Data Warehouse (DW) architecture, supporting Star Schema or Snowflake dimensional modeling, enabling queries and reports via OLAP (Online Analytical Processing) tools.

### 2.4 Data Processing: Construction of ETL (Extraction, Transformation, and Loading) pipelines to integrate dispersed data.

## 3. Software Engineering, DevOps, and Code Quality

### 3.1 DevOps Practices: Application and definition of DevOps tools throughout the project lifecycle, with proper technical justification for each choice.

### 3.2 Static Analysis: Implementation of static code analysis to ensure quality and security standards.

### 3.3 Automated Testing: The project must feature an automated testing strategy divided into:

#### 3.3.1 Unit and/or Integration Tests.

#### 3.3.2 Functional Tests at the system level (for both the API and the User Interface - UI).