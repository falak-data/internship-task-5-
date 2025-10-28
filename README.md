# internship-task-5-
Analyze monthly revenue and order volume.
This project analyzes monthly revenue and order volume from an online sales dataset using SQL.
Objective
The goal of this project is to calculate:
Total revenue per month
Total number of unique orders per month
Top 3 months with the highest revenue
Dataset
The dataset used is sales_data.csv which contains:
order_id
order_date
product_id
amount
Tools Used
MySQL
SQL aggregation functions
SQL Concepts Used
SUM() to calculate total revenue
COUNT(DISTINCT order_id) to count unique orders
EXTRACT(YEAR FROM order_date) and EXTRACT(MONTH FROM order_date) to group data by month and year

GROUP BY to aggregate

ORDER BY to sort results
