# SQL-Project-1

# SQL Employee Database Analysis

## Overview
This project involves designing tables, importing data from CSV files into a SQL database, and analyzing employee data from the 1980s and 1990s for a fictional company, Pewlett Hackard. The project encompasses data modeling, data engineering, and data analysis tasks.

## Table of Contents
- [Project Structure](#project-structure)
- [Data Modeling](#data-modeling)
- [Data Engineering](#data-engineering)
- [Data Analysis](#data-analysis)
- [Requirements](#requirements)
- [Usage](#usage)

## Project Structure
The project directory is organized as follows:
```
sql-challenge/
    ├── EmployeeSQL/
    │   ├── data/
    │   │   ├── departments.csv
    │   │   ├── dept_emp.csv
    │   │   ├── dept_manager.csv
    │   │   ├── employees.csv
    │   │   ├── salaries.csv
    │   │   └── titles.csv
    │   ├── sql_queries.sql
    │   └── ERD.png
    └── README.md
```

## Data Modeling
- Inspected the provided CSV files to understand the data structure and relationships.
- Created an Entity Relationship Diagram (ERD) to visualize the table schemas and their relationships.
- The ERD is included in the project repository as `ERD.png`.

## Data Engineering
- Designed table schemas for each of the six CSV files, specifying data types, primary keys, foreign keys, and constraints.
- Ensured that primary keys are unique and created composite keys where necessary.
- Created tables in the correct order to handle foreign key references.
- Imported the data from each CSV file into the corresponding SQL table.

## Data Analysis
Performed the following data analysis tasks using SQL queries:

1. Listed the employee number, last name, first name, sex, and salary of each employee.
2. Listed the first name, last name, and hire date for employees hired in 1986.
3. Listed the manager of each department along with their department number, department name, employee number, last name, and first name.
4. Listed the department number for each employee along with their employee number, last name, first name, and department name.
5. Listed the first name, last name, and sex of employees whose first name is "Hercules" and last name begins with "B".
6. Listed each employee in the Sales department, including their employee number, last name, and first name.
7. Listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. Listed the frequency counts, in descending order, of all the employee last names.

The SQL queries used for data analysis are stored in the `sql_queries.sql` file.

## Requirements
- PostgreSQL database
- SQL client (e.g., pgAdmin)

## Usage
1. Create a new PostgreSQL database for the project.
2. Execute the SQL queries in the `sql_queries.sql` file to create the necessary tables and import the data from the CSV files.
3. Use the provided SQL queries or create your own queries to perform data analysis on the imported employee data.

Feel free to explore the data and derive additional insights based on your analysis requirements.

For any questions or feedback, please contact [elluis.lr1@gmail.com].
