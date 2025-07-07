# 🛒 E-Commerce Data Analysis Using SQL

## 📌 Project Overview

This project simulates an e-commerce database and analyzes sales trends, customer behavior, and product performance using **MySQL**. The project is divided into three levels of difficulty — **Basic**, **Intermediate**, and **Advanced** — and demonstrates a variety of SQL skills useful for a **beginner Data Analyst**.

---

## 🗃️ Dataset Structure

The database `EcommerceDB` includes the following tables:

| Table Name     | Description                                   |
|----------------|-----------------------------------------------|
| `Customers`    | Contains customer information (name, location, registration date, etc.) |
| `Products`     | Product catalog with categories and prices    |
| `Orders`       | Orders placed by customers                    |
| `Order_Details`| Items within each order (many-to-many mapping) |

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `sql_files/create_tables.sql` | SQL code to create the database and tables |
| `sql_files/insert_data.sql`   | SQL code to populate tables with sample data |
| `csv_files/*.csv`             | CSV exports of the data |
| `README.md`                   | Project documentation |

---

## 🔍 SQL Query Levels

### 🟢 Basic Queries
- List all customers and orders
- Retrieve product information by category
- Show customer orders with names using JOIN
- Filter by date or price range
- Count total records and distinct values

### 🟡 Intermediate Queries
- Total sales per customer
- Monthly sales trends
- Product performance by quantity and revenue
- Average product prices by category
- Find top customers or products using aggregation

### 🔴 Advanced Queries
- Running totals using `WINDOW` functions
- Top orders per customer using `ROW_NUMBER()`
- Subtotals using `ROLLUP`
- Customers spending above global average
- Revenue contribution % per product

---

## 🎯 Skills Demonstrated

- SQL Database Design
- Data Cleaning & Insertion
- Joins (INNER, LEFT)
- Aggregations (`SUM`, `AVG`, `COUNT`, `GROUP BY`)
- Window Functions (`ROW_NUMBER`, `RANK`)
- Subqueries and CTEs
- Analytical SQL for business insights

---

## 🛠️ How to Use

1. Import `create_tables.sql` into your MySQL Workbench to create the schema.
2. Run `insert_data.sql` to populate the database.
3. Execute queries from each level to test and learn.
4. Use the `.csv` files for external reporting or BI tool integration.

---

## ✅ Use Case

This project is designed as a **portfolio project** for entry-level roles such as:

- Data Analyst
- Business Intelligence Intern
- SQL Developer (Beginner)

You can showcase it during interviews, in your resume, or as a GitHub project to demonstrate your SQL proficiency.

---

## 🧠 Author

**Avnish Ranjan**  
👨‍💻 B.Tech in Computer Science  


---

## 📌 License

This project is licensed under the MIT License — feel free to use and extend for learning and job preparation.
