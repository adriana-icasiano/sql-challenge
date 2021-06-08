# SQL Challenge


## Background
The data related to this assignment represents employee data at HP from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files. In this assignment, students will design the tables to hold data in the CSVs, and import the CSVs into a SQL database. In other words, students will perform:

1. Data Engineering

3. Data Analysis

#### Data Modeling

Inspect the CSVs and sketch out an ERD of the tables using QuickDBD [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com).

#### Data Engineering

* Create a table schema for each of the six CSV files, specifying data types, primary keys, foreign keys, and other constraints.

* For the primary keys check to see if the column is unique, otherwise create a [composite key](https://en.wikipedia.org/wiki/Compound_key). Which takes to primary keys in order to uniquely identify a row.

* Import each CSV file into the corresponding SQL table, importing the data in the same order that the tables were created and account for the headers when importing to avoid errors.

#### Data Analysis

After the database is complete, perform the following:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
