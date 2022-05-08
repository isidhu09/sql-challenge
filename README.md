# sql-challenge

This challenge incorporated three parts: data modeling, data engineering, and data analysis

Data Modeling
* Inspected the CSVs and sketched out an ERD of the tables

Data Engineering
* Used the provided information to create a table schema for each of the six CSV files
* Specified data types, primary keys, foreign keys, and other constraints
* Primary key column is unique. Otherwise, created a composite key, which takes two primary keys to uniquely identify a row
* Imported each CSV file into the corresponding SQL table

Data Analysis
* Listed the following details of each employee: employee number, last name, first name, sex, and salary
* Listed first name, last name, and hire date for employees who were hired in 1986
* Listed the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name
* Listed the department of each employee with the following information: employee number, last name, first name, and department name
* Listed first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B"
* Listed all employees in the Sales department, including their employee number, last name, first name, and department name
* Listed all employees in the Sales and Development departments, including their employee number, last name, first name, and department name
* Listed the frequency count of employee last names (i.e., how many employees share each last name) in descending order

Bonus Challenge
* Created visualizations of the data 
* Imported the SQL database into Pandas
* Password needs to be inputed in config.py file which is included in the gitignore
* Create a histogram to visualize the most common salary ranges for employees.
* Create a bar chart of average salary by title.

Observation on visualized data
* Salary averages by title look misleading. Naturally, one would expect a manager or senior position to have a higher average salary
* The distribution of salary ranges looks correct, as one would expect a higher concentration to be at the lower end 
