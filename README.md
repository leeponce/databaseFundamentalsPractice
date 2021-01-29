# databaseFundamentalsPractice
BVC Tech Skills Training Class Activities
1) Either create a dataset or search for a small dataset in the internet.
Use the commands you learned in Data Definition Language (DDL) to practice creating database tables, altering the tables, and dropping, deleting, and truncating the table using your dataset. 
Then, use Data Manipulation Language (DML) to practice inserting data, updating data, selecting information and displaying specific columns in the database. 
Present your work to class.
2) Then use UNION, INTERSECT and EXCEPT to see how they differ from the JOIN operation.
 Present your results to class.
3) Write a Query in SQL text editor to retrieve only those employees who work in the company’s ‘shipping’ department. The columns are first name and last name from employee table.
SELECT first_name, last_name
FROM employees
WHERE department = ‘shipping’
4) Write a SELECT DISTINCT Query for retrieving student column from Transcript table 

SELECT DISTINCT Student
	FROM table_Transcript
5) Write SQL statement to sort the results from the previous example in descending order
SELECT *
FROM table_grades
ORDER BY teacher DESC
6) Write a query for combining conditions 
 Retrieve employees who were hired after Jan 2018 and who work in the Accounting Department. Include employees first name, last name, and department name. Use employee table for your query
SELECT first_name, last_name, department
FROM employees
WHERE department = ‘accounting’ AND hired >= ‘2018-JAN-01’
7) Write a query using Between clause 
 Retrieve a list of employees who are hired between Jan 1980 and Dec 1985
SELECT first_name, last_name, hire_date
FROM employees
WHERE hire_date >= ‘1-Jan-1980’ AND hire_date <= ‘31-Dec-1985’
8) Write a query using NOT keyword 
 Retrieve a list of employees who don’t work in the marketing department.
SELECT first_name, last_name, department
FROM employees
WHERE NOT department = ‘marketing’
9) Use employee table in the dataset. Use the UNION clause to create a query that returns a list of all employees in the shipping department, as well as the list of the employees who were hired between January 1, 1990, and January 1, 2000.
10) SELECT first_name, last_name
FROM employees
WHERE department = ‘shipping’
UNION
SELECT first_name, last_name
FROM employeeshire
WHERE hire_date BETWEEN ‘1-Jan-1990’ AND ‘1-Jan-2000’
11) Your first query returns students’ grades from math_course table that are between A and C
Your second query returns students’ grades from math-course table that are between B and D 
 
Write the syntax for an INTERSECT statement to create a query that returns all rows from math-course table where grade is between B and C		
SELECT * FROM class_info 
		WHERE grade BETWEEN “A” AND “C”
		INTERSECT 
		SELECT * FROM class_info
		WHERE grade BETWEEN “B” AND “D”
12) Refer to the exercises in the book for Inserting Data and practice.
13) Refer to the exercises in the book for “Using the Update Statement” and practice.
14) Follow the instructions in your book to create a Unique Constraint using SQL Server Management Studio.
15) Follow the instructions in your book to Create a Foreign Key Using SQL Server Management Studio.
16) Follow the instructions in your book to Creating a Non-Clustered Index on a Table.
17) Conduct a research about SQL Server Security Model. 
What did you learn from your research?
Why is it important?
18) Follow instructions in your books to add a new login to SQL Server and removing a Windows login.
19) Follow instructions in your book to grant access to a database.
20) Read and Familiarize yourselves with the Fixed Database Roles in SQL Server and assigning Fixed Database Roles with SSMS and Transact-SQL. Add a user to a database role following the steps identified in the book
21) Read and Familiarize yourselves with object permissions.Modify Object’s permissions Set permissions from the user list and role list Grant permission with Transact-SQL Statements Manage Roles
22) Review a sample Security Model in your books.
23) Review Database Restore scenarios in SQL server

Follow instructions in your book to restore data using SSMS and Transact-SQL
24) 





