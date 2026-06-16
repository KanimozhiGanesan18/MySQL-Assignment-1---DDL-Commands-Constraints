# MySQL-Assignment-1---DDL-Commands-Constraints
MySQL Assignment 1 - DDL Commands, Constraints



As a Data Analyst, the company requires an Employee Database to store and manage information 
related to employees, departments, and locations within the organization.  

required to design and manage this employee database using MySQL DDL commands, 
focusing on creating, modifying, and managing database objects while enforcing appropriate 
constraints to ensure data integrity and consistency.


Dataset Description: 
You will work to create the following three tables:

● Table: Departments  

Attributes: 
○ department_id – Primary Key 
○ department_name 

● Table: Location  

Attributes: 
○ location_id – Primary Key 
○ location_name 
● Table: Employees  

Attributes: 
○ employee_id – Primary Key 

○ Employee_name 
○ Gender 
○ Age 
○ Hire_date 
○ Designation 
○ Salary 
○ department_id – Foreign Key referencing department(department_id) 
○ location_id—Foreign Key referencing location(location_id) 

Tasks:  

DDL Commands  

1. Database and Table Creation (CREATE): 

● Create a Database for this project  
● Create all three tables in MySQL with appropriate data types and relationships. 

2.  Table Alteration (ALTER) 

● Add a new column named "email" to the Employees table to store 
employee email addresses.  
● Modify the data type of the "designation" column in the Employees table to 
support a wider range of values.  
● Drop the “age” column from the Employees table.  
● Rename the “hire_date” column to “date_of_joining”.  

3. Table Renaming (RENAME): 

● Rename the "Departments" table to "Departments_Info".  
● Rename the "Location" table to "Locations".  

4. Table Truncation (TRUNCATE):  

● Truncate the Employees table.  

5. Database & Table Dropping (DROP):  

● Drop the Employees table and then the “employee” database.  

Tasks: Constraints - 

1. Database Recreation:  

● Drop the 'employee' database if it exists  
● Recreate it using the provided schema, ensuring that all tables are created 
with the appropriate constraints as instructed. 
● Establish links between the "department_id" and "location_id" fields in the 
"employees" table and their respective tables. 

2. Departments Table:  

● Ensure that the "department_id" uniquely identifies each department.  
● Set up constraints on the "department_name" to avoid duplicate and null 
entries. 

3. Locations Table:  

● Establish a mechanism to automatically generate unique identifiers for each 
location, ensuring that they are incremented sequentially.  
● Implement constraints to prevent the insertion of null and duplicate locations.  

4. Employees Table:  

●  Guarantee that each employee has a distinct identifier.  
● Create a restriction to ensure that the employee's name is always provided.  
● Limit the acceptable values for the "gender" field to only 'M' or 'F'.  
● Enforce a condition to ensure that the employee's age is 18 or above.  
● Automatically assign the current date to the "hire_date" field if not specified.  
