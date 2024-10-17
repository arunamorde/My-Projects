Employee Database Management Project

Overview This project involves creating and managing an employee database, including setting up tables, performing data transformations, and running various SQL queries to analyze employee data and perform necessary updates.

Table of Content Introduction: Database Setup: Task 1.1: Creating the Employees Table Task 1.2: Creating the Departments Table Data Transformations: Task 2.1: Altering the Employees Table Task 2.2: Creating Unique Keys Task 2.3: Cleaning ID Columns Task 2.4: Creating the Data Model Data Insertion: Task 3.1: Inserting Employee Data Task 3.2: Inserting Department Data Data Updates: Task 4.1: Promoting an Employee Task 4.2: Renaming Job Positions Task 4.3: Salary Increases for Analysts Data Analysis and Queries Task 5.1: Employee Information with Manager and Active Status Task 5.2: Creating a View for Employee Information Task 6: Average Salaries by Position Task 7: Average Salaries by Department Task 8: Salary Comparison by Job Position Task 9: Running Total of Salary Development Task 10: Running Total Considering Employee Departure Task 11: Top Earners by Position Task 12: Aggregations of Salary Data Task 13: Employee Salary Rankings by Department Task 14: Top Earners by Department Conclusion:

Introduction: The purpose of this project is to create a comprehensive employee database management system, handle data transformations, and perform analytical queries to manage and analyze employee data effectively.

Database Setup:

Task 1.1: Creating the Employees Table Create the employees table with the following columns:

emp_id INT PRIMARY KEY

first_name VARCHAR(255) NOT NULL

last_name VARCHAR(255) NOT NULL

position_title VARCHAR(255) NOT NULL

salary DECIMAL(10, 2)

start_date DATE NOT NULL

birth_date DATE NOT NULL

store_id INT

department_id INT

manager_id INT

end_date DATE

Task 1.2: Creating the Departments Table Create the departments table with the following columns:

department_id INT PRIMARY KEY

department_name VARCHAR(255) NOT NULL

Data Transformations: Task 2.1: Altering the Employees Table Set department_id to NOT NULL.

Add default value of CURRENT_DATE to start_date.

Add end_date column with appropriate data type.

Add birth_check constraint to ensure birth dates are not in the future.

Rename job_position column to position_title.

Task 2.2: Creating Unique Keys Create a unique key (GeoKey) in both employees and departments tables.

Task 2.3: Cleaning ID Columns Create a function to remove the “ID - ” part of the emp_id column in employees and department_id in departments.

Task 2.4: Creating the Data Model Connect all tables and use the existing Calendar table.

Data Insertion: Task 3.1: Inserting Employee Data Insert the provided employee data into the employees table.

Task 3.2: Inserting Department Data Insert the provided department data into the departments table.

Data Updates: Task 4.1: Promoting an Employee Promote Jack Franklin to 'Senior SQL Analyst' and increase his salary to 7200.

Task 4.2: Renaming Job Positions Rename the position title 'Customer Support' to 'Customer Specialist'.

Task 4.3: Salary Increases for Analysts Increase the salaries of all SQL Analysts (excluding Senior SQL Analysts) by 6%.

Data Analysis and Queries: Task 5.1: Employee Information with Manager and Active Status Add manager column with first name and last name combined and is_active column to indicate if the employee is still with the company.

Task 5.2: Creating a View for Employee Information Create a view v_employees_info from the previous query.

Task 6: Average Salaries by Position Query to return average salaries for each position with appropriate roundings.

Task 7: Average Salaries by Department Query to return average salaries for each department.

Task 8: Salary Comparison by Job Position Query to return salary comparison for each job position, and count how many people earn less than their average position salary.

Task 9: Running Total of Salary Development Query to return a running total of salary development ordered by start_date.

Task 10: Running Total Considering Employee Departure Query to return a running total considering employees who have left the company.

Task 11: Top Earners by Position Query to return top earners by position including average salary and filtering out employees with salaries equal to their position's average.

Task 12: Aggregations of Salary Data Query to return all meaningful aggregations of salary data grouped by division, department, and position title.

Task 13: Employee Salary Rankings by Department Query to return all employees with their salary rank partitioned by department.

Task 14: Top Earners by Department Query to return the top earner of each department.

Conclusion: This project successfully set up an employee database, performed necessary data transformations, and executed various SQL queries to manage and analyze employee data effectively. The queries provided insightful information on employee roles, salaries, and departmental structures.


Maven Market Power BI Report

Overview This repository contains the files used for the analysis and report creation for Maven Market, a multi-national grocery chain with locations in Canada, Mexico, and the United States. The main Power BI report file is MavenMarket_Report.pbix.

Key Responsibilities Data Import and Cleansing: Imported and cleaned data from various sources to ensure accuracy and consistency. Data Integration: Integrated data into a unified model with lookup tables and hierarchies. DAX Measures: Developed DAX measures to calculate key metrics and insights.

Report Design: Created an interactive report using various visualizations such as matrices, KPI cards, maps, and charts to analyze Maven Market's performance and support decision-making.

Contents: Maven Market Business Problems File contains the business Problems. Maven Market Solution file contains the required solutions.

Conclusion: Delivered detailed reports that highlighted key performance indicators (KPIs) and trends, enabling stakeholders to make data-driven decisions. Provided actionable insights into sales performance, customer behavior, and product trends, driving strategic initiatives.




