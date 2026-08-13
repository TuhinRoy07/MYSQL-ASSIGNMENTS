MySQL Employee Management Assignment

📌 Overview

This project contains basic MySQL operations for creating and managing
an employees table.

The queries cover:

Creating a database

Creating a table

Adding employee records

Adding comments to columns

Selecting and filtering data

Using DISTINCT

Adding a new column

Using LIMIT

Using column aliases with AS

Inserting additional employee data

🗄️ Database

Database Name: assignments

Table Name: employees

🔧 SQL Operations Performed

1. Create Database and Table

The database assignments is created and the employees table is
created with the following columns:

id

name

department

salary

join_date

2. Insert Employee Records

Five initial employee records are inserted into the table.

3. Modify Column Comment

A comment is added to the salary column to describe it as the
employee's monthly salary.

4. Retrieve All Employees

SELECT * FROM employees;

5. Display Unique Departments

SELECT DISTINCT department FROM employees;

6. Filter IT Department Employees

SELECT * FROM employees WHERE department = 'IT';

7. Add Email Column

ALTER TABLE employees ADD COLUMN email VARCHAR(100);

8. Display First Three Records

SELECT * FROM employees LIMIT 3;

9. Use Column Aliases

SELECT name AS 'Employee Name', salary AS 'Monthly Salary'
FROM employees;

10. Insert an Additional Employee

An additional employee, Eva Green, is inserted with an email address.

📸 MySQL Execution Screenshots

Add screenshots of your MySQL queries and their output in this section.

Screenshot 1 --- Database and Table Creation

Add your screenshot here.

![Database and table creation](screenshots/database-table-creation.png)

Screenshot 2 --- Employee Data

Add your screenshot here.

![Employee data](screenshots/employee-data.png)

Screenshot 3 --- Filtering and DISTINCT

Add your screenshot here.

![Filtering and distinct queries](screenshots/filtering-distinct.png)

Screenshot 4 --- Email Column and Additional Employee

Add your screenshot here.

![Email column and additional employee](screenshots/email-column.png)

Screenshot 5 --- LIMIT and Column Aliases

Add your screenshot here.

![Limit and aliases](screenshots/limit-alias.png)

📂 Suggested Project Structure

assignment1,13.08.2026/
│
├── assignment1,13.08.2026.sql
├── README.md
│
└── screenshots/
    ├── database-table-creation.png
    ├── employee-data.png
    ├── filtering-distinct.png
    ├── email-column.png
    └── limit-alias.png

👨‍💻 Author

Tuhin Roy
