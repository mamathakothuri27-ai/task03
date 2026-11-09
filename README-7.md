# Task 3: SQL for Data Analysis

## Objective
Use SQL queries to extract and analyze structured data from an e-commerce database.

## Tools
- MySQL 8.0+
- MySQL Workbench or another MySQL client

## Dataset
This project creates a small sample e-commerce database named `ECommerce_SQL_Database`.
The SQL file creates four tables (`customers`, `products`, `orders`, and `order_items`) and inserts sample records. No separate dataset download is required.

## Files
- `task3_sql_data_analysis.sql` — database setup, sample data, analysis queries, view, indexes, and EXPLAIN example.

## How to run
1. Open MySQL Workbench and connect to your MySQL server.
2. Open `task3_sql_data_analysis.sql`.
3. Execute the complete script.
4. Review each query's result grid. If your SQL editor does not allow the whole script to run at once, execute it section by section.
5. Capture screenshots of the query and its output for the submission.

## Concepts demonstrated
- `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`
- Aggregate functions: `COUNT`, `SUM`, `AVG`
- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`
- Subqueries
- Revenue calculation and average revenue per customer
- Views using `CREATE OR REPLACE VIEW`
- Indexes and query-plan inspection with `EXPLAIN`
- NULL handling with `COALESCE`

## Notes
This script uses MySQL syntax. `CREATE OR REPLACE VIEW` and `RIGHT JOIN` are supported in MySQL 8.0+. The sample data is fictional and is included only for learning and demonstration.
