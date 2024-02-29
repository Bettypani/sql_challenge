# sql_challenge

This project is divided into three main parts: data modeling, data engineering, and data analysis.

Data Modeling
An Entity Relationship Diagram (ERD) has been created to represent the structure of the data in the provided CSV files. The ERD illustrates the relationships between different entities in the database schema.

Data Engineering
Table schemas have been created for each of the six CSV files. The schemas include data types, primary keys, foreign keys, and other constraints necessary for data integrity and consistency. Tables are created in the correct order to handle foreign keys, ensuring referential integrity.

The CSV files have been imported into their corresponding SQL tables.

Data Analysis
Several SQL queries have been formulated to perform various analyses on the provided data. These queries address specific questions and extract relevant information from the database.

List employee details such as employee number, last name, first name, sex, and salary.
List employees hired in 1986, including their first name, last name, and hire date.
List department managers along with their department number, department name, employee number, last name, and first name.
List department details for each employee, including department number, employee number, last name, first name, and department name.
Filter employees named Hercules with last names starting with B, displaying their first name, last name, and sex.
List employees in the Sales department, including their employee number, last name, and first name.
List employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
Show the frequency counts of employee last names, sorted in descending order.

Files
ERD.png: Image file containing the Entity Relationship Diagram (ERD).
schema.sql: SQL file containing table schemas and import statements for CSV files.
queries.sql: SQL file containing queries for data analysis.
README.md: This readme file providing an overview of the project.

Instructions
Review the provided ERD to understand the data model.
Execute the schema.sql file to create the necessary tables and import data from the CSV files.
Execute the queries in the queries.sql file to perform various data analyses.
