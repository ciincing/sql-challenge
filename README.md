# sql-challenge

## Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

## Data Modeling
I inspected the CSV files and then sketched an Entity Relationship Diagram of the tables. To create the sketch, I used a tool like QuickDBDLinks to an external site.

## Data Engineering
I used the provided information to create a table schema for each of the six CSV files. I made sure to specify the data types, primary keys, foreign keys, and other constraints as needed.

For the primary keys, I verified that each column was unique. In cases where it wasn't, I created composite keys that required two primary keys to uniquely identify a row.

To handle the foreign keys properly, I ensured that I created the tables in the correct order.

Additionally, I successfully imported each CSV file into its corresponding SQL table.

## Data Analysis 
I listed the employee number, last name, first name, sex, and salary of each employee.

I listed the first name, last name, and hire date for the employees who were hired in 1986.

I listed the manager of each department along with their department number, department name, employee number, last name, and first name.

I listed the department number for each employee along with that employee’s employee number, last name, first name, and department name.

I listed the first name, last name, and sex of each employee whose first name was Hercules and whose last name began with the letter B.

I listed each employee in the Sales department, including their employee number, last name, and first name.

I listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

I listed the frequency counts, in descending order, of all the employee last names (that is, how many employees shared each last name).
