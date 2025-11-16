# 🍕 Pizza Sales SQL Project – Complete Project Description
This project is a comprehensive SQL-based analysis of pizza sales data for a restaurant business. It focuses on creating a structured database, loading operational datasets, and running analytical SQL queries to extract meaningful insights about orders, revenue, customer trends, and product performance.

- Using SQL, the project demonstrates how a data analyst can transform raw transactional data into actionable insights that support decision-making in the food service industry.

🎯 Project Objectives :
- Design a relational database for pizza sales
- Import and organize order data, pizza details, categories, and sizes
- Analyze total revenue, sales trends, and order volume
- Identify best-selling and worst-selling pizzas
- Evaluate category-wise and size-wise performance
- Generate KPIs using SQL queries
- Demonstrate SQL skills (joins, aggregations, CTEs, window functions, subqueries)

🧰 Tech Stack :
Database
- MySQL (used in the SQL file)

Languages
- SQL (DDL + DML + analytical queries)

Tools
- MySQL Workbench
SQL Server / PostgreSQL (optional)

🗄️ Database Schema :
The SQL file creates and uses a database named pizzahut, containing the following tables:
1. orders
- Stores high-level order information including:
  (a) order_id
  (b) order_date
  (c) order_time

2. order_details
- Contains item-level information:
  (a) order_details_id
  (b) order_id (FK)
  (c) pizza_id
  (d) quantity

3. pizzas
- Includes all pizza items the restaurant offers:
  (a) pizza_id
  (b) pizza_type_id
  (c) size
  (d) price

4. pizza_types
- Describes pizza varieties:
  (a) pizza_type_id
  (b) name
  (c) category
  (d) ingredients
  
# 📊 Key Analyses Performed
The SQL file contains more than 40 business-focused queries, including:
✔ Total revenue generated
# SELECT SUM(order_details.quantity * pizzas.price) AS total_sales
✔ Top-selling and least-selling pizzas
✔ Category-wise revenue and order distribution
✔ Pizza size performance analysis
✔ Daily, weekly & monthly sales trends
✔ Peak ordering hours
✔ Revenue contribution by pizza type
✔ Average Order Value (AOV)
✔ CTEs and window function analyses

- Ranking pizzas by revenue
- Running totals
- Percentage contributions
- This collection of queries helps provide insights that a restaurant might use for inventory planning, menu adjustments, marketing, and staffing.

📁 Project Structure
pizza_sales_sql_project/
│
├── data/                     # (Optional) CSV datasets
│
├── sql/
│   ├── pizzahut_database.sql    # Your SQL schema + analysis queries
│
├── README.md

👨‍💻 Developed By
-- Ayush
SQL | Data Analysis | BI | Python
- 🔗 GitHub: https://github.com/ayush13-0
- 🔗 LinkedIn: https://www.linkedin.com/in/ayush130
