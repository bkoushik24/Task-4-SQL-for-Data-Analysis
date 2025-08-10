# Task-4-SQL-for-Data-Analysis
This task involves creating and querying an e-commerce database using SQL. It covers essential SQL operations including SELECT, WHERE, GROUP BY, ORDER BY, JOIN types, subqueries, aggregate functions, views, and index creation. The dataset is modeled with customers, orders, order_items, products, and categories tables. 

📌 Objective
The objective of this task is to use SQL queries to extract, manipulate, and analyze structured data from an e-commerce database. This includes performing selections, filtering, aggregations, joins, subqueries, creating views, and optimizing queries with indexes.

🛠 Tools & Technologies
- **Database**: MySQL / PostgreSQL / SQLite
- **Language**: SQL
- **Client**: MySQL Workbench / pgAdmin / DB Browser for SQLite

📂 Dataset Structure
The e-commerce database contains the following tables:
1. **customers** – Customer details
2. **categories** – Product categories
3. **products** – Product details with prices and stock
4. **orders** – Orders placed by customers
5. **order_items** – Products included in each order

📜 Queries Implemented
1. **Basic Selection** – Retrieve first 10 customers  
2. **Filtering with WHERE** – Orders above $500  
3. **Aggregation + GROUP BY** – Total sales per customer  
4. **INNER JOIN** – Orders with customer details  
5. **LEFT JOIN** – Customers without orders  
6. **Subquery** – Products with price above average  
7. **Aggregate Functions** – Average order value  
8. **Creating Views** – Monthly sales summary  
9. **Index for Optimization** – Index on `order_date` for faster queries  

📊 Example Insights
- Identify **top customers** by spending.
- List **high-value orders**.
- Detect **inactive customers**.
- Summarize **monthly sales trends**.
- Optimize performance with **indexes**.

📷 Deliverables
- **SQL File**: `task4_data_analysis.sql` (schema + queries)
- **Screenshots**: Query results from database client.

## 🚀 How to Run
1. Import the provided SQL schema and dataset into your database.
2. Run the queries from `task4_data_analysis.sql` in your SQL client.
3. Verify results and take screenshots for documentation.

---
