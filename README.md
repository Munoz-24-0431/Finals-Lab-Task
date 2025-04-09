# [Finals-Lab-Task-1](https://github.com/user-attachments/files/19664008/LAB.TASK.1.docx) - MySQL Basics
This project demonstrates the creation of a basic relational database in MySQL. It includes the setup of five related tables:
- employees: Stores employee details with self-referencing manager IDs.
- departments: Contains department names.
- employee_departments: Many-to-many relationship between employees and departments.
- employee_projects: Tracks which projects each employee is working on.
- managers: Stores manager records linked to employees.

The schema includes primary keys, foreign keys, and relationships between tables to ensure referential integrity.

## Step by Step Process
**1. Create a table named employees with the following fields:**
- employee id: Unique integer, auto-increment, primary key.
- employee_name: String (VARCHAR) with up to 255 characters, not null.
- manager_id: Integer, foreign key referencing employee_id in the same table (employees).

**2. Create a table named departments with the following fields:**
- department_id: Unique integer, auto-increment, primary key.
- department name: String (VARCHAR) with up to 255 characters, not null.

**3. Create a table named employee_departments with the following fields:**
- employee_id: Integer, foreign key referencing employee_id in employees.
- department_id: Integer, foreign key referencing department id in departments.
- Composite primary key (employee id, department id). 



**4. Create a table named employee_projects with the following fields:**
- employee_id: Integer, foreign key referencing employee_id in employees.
- project_name: String (VARCHAR) with up to 255 characters, not null.

**5. Create a table named managers with the following fields:**
- manager_id: Unique integer, auto-increment, primary key.
- employee_id: Integer, foreign key referencing employee_id in employees.

## QUERY STATEMENT, TABLE STRUCTURES, AND ERD (SCREENSHOTS)

- **TASK 1: QUERY STATEMENT**
![Image](https://github.com/user-attachments/assets/58bfff54-c1b8-444d-ba4f-7c7e4a634558)

- **TABLE STRUCTURE**
![Image](https://github.com/user-attachments/assets/4c18cd4d-d45d-4ca7-9350-ab84d06bf5da)

- **TASK 2: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/7c570fc5-664a-40c5-8783-9802a74b05d1)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/ece77b87-6809-4141-ab85-fee609600818)

- **TASK 3: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/37093170-9f38-4c8c-886e-3617301c5aca)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/04bcae53-1237-4f4d-b9ad-74a283b1e428)

- **TASK 4: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/ae14b061-596d-4b06-a262-96b386892d59)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/56349cd4-8332-4f74-8fa5-69a59f3dd89c)

- **TASK 5: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/d27b9578-2eb4-48ec-811f-2fda4d32af7f)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/81238acc-1e77-4025-83ff-bf367cc6ad4e)

- **ERD**
![image](https://github.com/user-attachments/assets/e1e6ad7b-5f04-40f7-95c7-052566abbfac)
