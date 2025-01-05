# Salseman-Customer-System_SQL-project
This repository features a SQL project completed during my Oracle SQL training at Qspider. It involves creating and managing three interconnected tables (Salesmen, Customer, Order) to perform database operations, practice SQL queries, and explore key concepts like joins, constraints, and Database Structure
# Tables:
# Salesmen:
Contains information about salespeople, including their ID, name, city, and commission.
# Constraints:
Primary key (SNUM) must start with 'S.'
Non-null values for SNAME.
# Customer:
Contains customer details, including their ID, name, city, rating, and salesperson assigned.
Constraints:
# Primary key (CNUM) must start with 'C.'
Non-null values for CNAME.
# Order:
Represents orders made by customers, with information about order ID, amount, date, customer ID, and salesperson ID.
# Constraints:
Primary key (ONUM) must start with 'O.'
Non-null values for AMT.
Queries Performed
# Basic SELECT Queries:
Retrieve all information from the Salesmen table.
Display specific columns (SNUM, SNAME, CITY) from the Salesmen table.
Extract order details, including order date, salesperson ID, order number, and amount.
Fetch unique orders and other specific query use cases.
# Operators and Filtering:
Utilize comparison operators (>, <, =, !=) and logical operators (AND, OR, NOT) to filter data.
Perform searches using the IN, BETWEEN, and LIKE operators.
# Aggregate Functions:
Calculate sum, average, and count of specific fields like order amounts and ratings.
Group data to find maximum, minimum, or summarized values (e.g., largest order for each salesperson).
# Joins and Relationships:
Perform inner joins to link related data between Salesmen, Customer, and Order tables.
Display combined results, such as orders with customer and salesperson names.
# Special Cases:
Handle NULL values in the database.
Use correlated subqueries for complex filtering and matching.

# Database Modifications:
Insert new rows into the database.
Update records (e.g., adjust ratings or commission rates).
Delete specific records based on given conditions.
# Advanced Queries:
Identify patterns, such as customers with above-average ratings or orders above specific amounts.
Create unions and use subqueries for advanced data retrieval.
# Additional Tasks:
Create and manipulate new tables, such as London_staff.
Perform cascading updates and deletions based on conditions.
Practical Use Cases

## This project is ideal for practicing SQL concepts such as:
Writing efficient queries
Understanding table relationships
Applying database constraints
Managing data consistency

## How to Use
Use the provided queries as practice tasks or modify them to suit your learning goals.
Explore and expand upon the tasks to deepen your understanding of SQL.
