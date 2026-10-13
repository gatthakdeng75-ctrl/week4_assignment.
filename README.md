# Week 4 Database Assignment: Advanced SQL Queries and Aggregations

## Description
This assignment focuses on advanced SQL queries and aggregate functions using MySQL. It demonstrates how to calculate totals and averages, find maximum values, group records, sort results, and limit query output.

## Learning Objectives
- Use aggregate functions such as `SUM()`, `AVG()`, and `MAX()`.
- Apply `GROUP BY` to group records.
- Use `ORDER BY` to sort query results.
- Use `LIMIT` to restrict the number of returned rows.
- Calculate the total price of products ordered.

## Database
The assignment uses the `sales` database and the following tables:
- `payments`
- `customers`
- `orderdetails`

## Assignment Questions

### Question 1: Total Payment Amount by Date
Calculates the total payment amount for each payment date, sorts the dates from newest to oldest, and displays only the five latest payment dates.

### Question 2: Average Credit Limit by Customer
Calculates the average credit limit and displays the customer name and country.

### Question 3: Total Price of Products Ordered
Calculates the total price using the quantity ordered and the price of each product, grouped by product code and quantity ordered.

### Question 4: Highest Payment Amount by Check Number
Finds the highest payment amount for each check number using the `MAX()` function.

## How to Run
1. Open MySQL Workbench.
2. Connect to your MySQL server.
3. Select the database by running `USE sales;`.
4. Execute the SQL queries in the file `week4_assignment.sql`.
5. Review the result grids for all four questions.

## Files
- `week4_assignment.sql` — Contains the SQL queries for all four assignment questions.
- `README.md` — Provides an overview of the assignment and explains how to execute the queries.

## Conclusion
This assignment helped me practice SQL aggregation, grouping, sorting, and limiting query results using MySQL.
