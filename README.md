# sql-challenge

Goal is to create  and analysis tables that make sense of the old CSV files from the 1980's and 1990's at the company Pewlett Hackard.

# Data Modeling
Looked over the old files to find connections and mapped out those connections using the app Entity Relationship Diagram (https://app.quickdatabasediagrams.com/). Exported the Entity Relationship Diagram and PostgreSQL code made by the diagraming app.
![QuickDBD-export](https://user-images.githubusercontent.com/119066378/221427006-3977755e-4366-4245-a137-4c0d2e44006c.png)

# Data Engineering
The PostgreSQL code was downloaded and made ready for the importing of the old CSV files to their respective created table. A new SQL file was opened and named Data Analysis to create tables from the old CSV files. The questions answered  by the Data Analysis SQL file are. List the employee number, last name, first name, sex, and salary of each employee. List the first name, last name, and hire date for the employees who were hired in 1986. List the manager of each department along with their department number, department name, employee number, last name, and first name. List the department number for each employee along with that employee’s employee number, last name, first name, and department name. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B. List each employee in the Sales department, including their employee number, last name, and first name. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name. List the frequency counts, in descending order, of all the employee last names.
