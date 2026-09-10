☕ Monday Coffee — Data Analysis Using SQL
📌 Project Overview

This project focuses on analyzing coffee sales data using PostgreSQL to answer practical business questions and generate meaningful insights.

The analysis uses information about cities, customers, products, and sales to understand customer behavior, sales performance, product demand, estimated coffee consumption, and monthly sales growth.

The main objective of this project is to strengthen practical SQL and analytical skills by solving business-oriented problems using real-world-style data.

🗂️ Dataset

The project contains four main tables:

City — City information, population, rank, and estimated rent
Customers — Customer information and city mapping
Products — Coffee product details
Sales — Sales transactions, dates, customers, products, and sales amounts
🔗 Table Relationship
City
  │
  └── Customers
        │
        └── Sales
              │
              └── Products
📊 Business Questions & Analysis
1. Coffee Consumers Count

Estimated the number of coffee consumers in each city by assuming that 25% of the population consumes coffee.

2. Total Revenue from Coffee Sales

Calculated total coffee sales revenue for each city during Q4 2023 and ranked cities based on revenue.

3. Sales Count for Each Product

Analyzed the number of units/orders sold for each coffee product.

4. Average Sales Amount per City

Calculated total sales, unique customers, and average sales per customer for each city.

5. City Population & Coffee Consumers

Compared city population, current customers, and estimated coffee consumers.

6. Top 3 Selling Products by City

Identified the top three products in each city using the DENSE_RANK() window function.

7. Customer Segmentation by City

Categorized coffee products and analyzed the number of unique customers purchasing a specific coffee category in each city.

8. Average Sales vs Rent

Compared average sales per customer with estimated rent per customer to understand the relationship between sales potential and rental cost.

9. Monthly Sales Growth

Calculated month-over-month sales growth for each city using the LAG() window function.

🛠️ SQL Concepts Used
SELECT
WHERE
GROUP BY
ORDER BY
JOIN
CTE (WITH)
Aggregate Functions
CASE
COUNT()
COUNT(DISTINCT)
SUM()
ROUND()
EXTRACT()
TO_CHAR()
LAG()
DENSE_RANK()
PARTITION BY
Date & Time Functions
Percentage Growth Calculations
🎯 Key Learning Outcomes

Through this project, I practiced converting business questions into SQL queries and improved my understanding of:

Data aggregation and filtering
Working with multiple related tables
Writing structured queries using CTEs
Using window functions for ranking and time-series analysis
Calculating business metrics and growth rates
Handling date-based analysis
Comparing multiple business KPIs
🚀 Project Goal

The goal of this project is not only to write SQL queries but to develop the ability to think analytically, understand business requirements, and convert them into meaningful data insights.

This project is part of my ongoing journey toward becoming a Data Analyst.
