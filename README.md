# [Finals-Lab-Task-1](https://github.com/user-attachments/files/19664008/LAB.TASK.1.docx) - MySQL Basics
This project demonstrates the creation of a basic relational database in MySQL. It includes the setup of five related tables:
- **employees:** Stores employee details with self-referencing manager IDs.
- **departments:** Contains department names.
- **employee_departments:** Many-to-many relationship between employees and departments.
- **employee_projects:** Tracks which projects each employee is working on.
- **managers:** Stores manager records linked to employees.

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
![image](https://github.com/user-attachments/assets/ef966274-c4ec-4e08-aa50-db517d28a0ff)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/bd369d7d-087f-4f80-90ce-f1107400616f)

- **TASK 3: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/92a4d073-21c0-41e7-9c44-9038962cfd0a)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/fa44f4a7-1b9b-437c-aa5d-c744ac24b8cc)

- **TASK 4: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/28ac6a81-7d1a-44bc-aade-230f2a03960d)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/b2998884-7497-4f91-b55d-f935ccb5d526)

- **TASK 5: QUERY STATEMENT**
![image](https://github.com/user-attachments/assets/7b6c84bc-9033-4380-99a9-851e4d1af226)

- **TABLE STRUCTURE**
![image](https://github.com/user-attachments/assets/93138753-48e1-46a2-ae44-c7908e84c6fd)

- **ERD**
![image](https://github.com/user-attachments/assets/2603a987-b5d4-49e9-941e-bdc33f14c0f7)
