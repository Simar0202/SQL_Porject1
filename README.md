E-Commerce Sales Analysis Using SQL
Project Overview

This project analyzes an e-commerce dataset using SQL to uncover valuable business insights related to customer behavior, product performance, sales trends, return patterns, and revenue growth.

The analysis utilizes advanced SQL concepts such as Common Table Expressions (CTEs), correlated subqueries, aggregate functions, and window functions to solve real-world business problems and support data-driven decision-making.

Dataset Description

The dataset contains transactional records from an e-commerce business.

Key Columns
Order ID
Customer ID
Product Name
Category
Quantity
Unit Price
Order Date
Country
Payment Method
Order Status

The dataset was analyzed to identify revenue drivers, customer purchasing patterns, product performance, and operational opportunities.

Project Objectives
Identify top revenue-generating customers.
Measure category-wise revenue contribution.
Analyze customer purchasing behavior and retention.
Track revenue growth over time.
Evaluate the impact of product returns.
Identify high-performing and underperforming products.
Discover opportunities for business growth and optimization.
SQL Analysis
1. Top 10 Customers by Revenue

Purpose: Identify customers generating the highest revenue.

SQL Concepts Used: GROUP BY, ORDER BY, LIMIT

2. Revenue Contribution by Category

Purpose: Measure the percentage contribution of each category to total revenue.

SQL Concepts Used: CTEs, Aggregate Functions

3. Repeat Customers

Purpose: Identify customers who placed multiple orders.

SQL Concepts Used: GROUP BY, HAVING

4. Most Returned Products

Purpose: Determine products with the highest return frequency.

SQL Concepts Used: Filtering, Aggregation

5. Monthly Revenue Trend

Purpose: Analyze revenue fluctuations across different months.

SQL Concepts Used: Date Functions, Aggregation

6. Running Total Revenue

Purpose: Track cumulative revenue growth over time.

SQL Concepts Used: Window Functions

7. Rank Customers Based on Spending

Purpose: Rank customers according to total spending.

SQL Concepts Used: DENSE_RANK(), Window Functions

8. Top Product in Each Category

Purpose: Identify the highest revenue-generating product within each category.

SQL Concepts Used: RANK(), PARTITION BY

9. Customers Spending Above Average

Purpose: Find customers spending more than the average customer.

SQL Concepts Used: Correlated Subqueries

10. Inactive Customers

Purpose: Identify customers who have not placed an order within the last 90 days.

SQL Concepts Used: Date Functions, HAVING

11. Customers Buying from Multiple Categories

Purpose: Identify customers purchasing across multiple categories.

SQL Concepts Used: COUNT(DISTINCT)

12. Revenue Lost Due to Returns

Purpose: Calculate revenue lost because of returned orders.

SQL Concepts Used: Aggregation, Filtering

13. Most Popular Payment Method per Country

Purpose: Determine preferred payment methods across countries.

SQL Concepts Used: Window Functions, Ranking

14. Month-over-Month Growth Rate

Purpose: Measure monthly revenue growth using previous month's revenue.

SQL Concepts Used: LAG(), Window Functions

15. Products Never Returned

Purpose: Identify products with zero recorded returns.

SQL Concepts Used: NOT EXISTS, Subqueries

16. Products Contributing More Than 10% of Category Revenue

Purpose: Identify key revenue-driving products within categories.

SQL Concepts Used: Correlated Subqueries

17. Products with Declining Monthly Sales

Purpose: Detect products experiencing decreasing sales trends.

SQL Concepts Used: LAG(), Window Functions

18. Fastest-Growing Product Month-over-Month

Purpose: Identify products with the strongest sales growth.

SQL Concepts Used: Window Functions, Growth Analysis

Key Business Insights
--- Customer Insights
High-value customers contribute a significant share of total revenue.
Repeat customers play an important role in business growth.
Customers purchasing across multiple categories show stronger engagement.
Inactive customers represent potential reactivation opportunities.
---- Product Insights
A small number of products drive a large portion of category revenue.
Certain products experience unusually high return volumes.
Some products maintain excellent customer satisfaction with zero returns.
Several products show declining sales trends and require attention.
Fast-growing products present strong expansion opportunities.
----Revenue Insights
Revenue trends reveal seasonal patterns in customer demand.
Month-over-month analysis highlights periods of growth and slowdown.
Product returns directly reduce business profitability.
Running revenue totals provide visibility into long-term growth.
Payment & Market Insights
Payment preferences vary by country.
Understanding regional payment behavior can improve customer experience and conversion rates.
------Business Recommendations
Launch loyalty programs for high-value customers.
Implement targeted campaigns for inactive customers.
Investigate products with high return rates.
Increase inventory availability for top-performing products.
Promote fast-growing products through marketing initiatives.
Develop category-specific growth strategies.
Optimize payment options based on regional customer preferences.
------Challenges Faced
Implementing month-over-month growth calculations using window functions.
Identifying products never returned using NOT EXISTS.
Calculating category-level revenue contributions using CTEs.
Performing customer segmentation based on purchasing behavior.
Tracking cumulative revenue using running totals.
---------SQL Concepts Demonstrated
Aggregate Functions
GROUP BY
HAVING
Common Table Expressions (CTEs)
Correlated Subqueries
Window Functions
RANK()
DENSE_RANK()
LAG()
Running Totals
Date Functions
Conditional Filtering
Business KPI Analysis
