# 🛒 Walmart Sales Analysis | SQL Project

## 📌 Project Overview

This project focuses on analyzing Walmart sales data using SQL and PostgreSQL to extract meaningful business insights.

The analysis explores sales performance, product categories, customer ratings, payment preferences, city-wise revenue, and branch-level performance.

The main objective is to use SQL queries to transform raw sales data into meaningful information that can support business decision-making.

## 🎯 Project Objectives

- Analyze Walmart sales transactions.
- Identify high-performing product categories.
- Calculate estimated revenue and quantity sold.
- Understand customer payment preferences.
- Evaluate customer ratings across cities and branches.
- Identify cities generating the highest estimated revenue.
- Apply advanced SQL techniques to solve business problems.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| PostgreSQL | Database management |
| pgAdmin 4 | SQL query execution |
| SQL | Data analysis |
| VS Code | Project development |
| Git & GitHub | Version control |

## 📂 Dataset Description

The project uses a Walmart sales dataset containing transaction-level information.

Key columns used in the analysis:

- City
- Branch
- Category
- Unit Price
- Quantity
- Payment Method
- Rating

## 📊 SQL Analysis & Business Questions

### 1. Basic Data Exploration
- Retrieve all records from the dataset.
- Display selected columns such as City, Category, Unit Price, and Quantity.
- Identify unique cities and product categories.
- Find transactions where unit price is greater than 50.
- Identify transactions where quantity is greater than 5.
- Retrieve cash payment transactions.
- Display the top 10 records with the highest unit price.
- Calculate the total number of records.
- Identify distinct payment methods.

### 2. Sales & Revenue Analysis
- Calculate the total number of transactions for each city.
- Calculate average unit price for each product category.
- Calculate total quantity sold for each product category.
- Identify the city with the highest average unit price.
- Calculate estimated revenue for each product category.
- Identify the highest revenue-generating product category.
- Find the top 3 product categories by estimated revenue.
- Rank cities based on estimated revenue using DENSE_RANK().

### 3. Payment Method Analysis
- Identify the most popular payment method based on transaction count.
- Calculate the percentage contribution of each payment method to total transactions.
- Compare the number of transactions and quantity sold across payment methods.

### 4. Customer Rating Analysis
- Calculate average customer ratings for each city.
- Identify product categories with an average rating greater than 7.
- Find cities with average ratings higher than the overall average rating.
- Identify the highest-rated transaction in each city using ROW_NUMBER().

### 5. Advanced SQL Analysis
- Rank cities based on estimated revenue using DENSE_RANK().
- Identify the highest-rated product category in each branch using RANK().
- Use subqueries to compare city-level ratings against overall ratings.
- Apply window functions to rank transactions and categories.

## 💻 SQL Concepts & Techniques Used

**Basic SQL**
- SELECT
- DISTINCT
- WHERE
- ORDER BY
- LIMIT

**Aggregate Functions**
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

**Grouping & Filtering**
- GROUP BY
- HAVING

**Advanced SQL**
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- PARTITION BY

**Additional Techniques**
- Percentage calculations
- Mathematical operations
- ROUND()
- Type Casting
- Revenue calculations

## 💡 Business Value

This analysis helps businesses understand:

- Which product categories generate the highest estimated revenue.
- Which cities contribute more to overall sales.
- Which payment methods are most frequently used.
- How customer ratings vary across cities.
- Which product categories receive higher customer ratings across branches.
- How transaction and quantity patterns differ by payment method.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Writing SQL queries for real-world business scenarios.
- Exploring and analysing structured datasets.
- Performing data aggregation and filtering.
- Working with subqueries and CTEs.
- Applying SQL window functions.
- Solving business problems using data-driven approaches.
- Managing and publishing projects using Git and GitHub.

## 👩‍💻 Author

**Sakshi Bankar**

Aspiring Data Analyst | SQL | PostgreSQL | Python | Data Analytics

GitHub: [sakshi9766](https://github.com/sakshi9766)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
