# Grocery-Store-Management
- This is my Grocery Store Management System developed using SQL. I created this project to organize and manage all grocery store operations—such as customers, products, suppliers, employees, orders, and order details—inside a clean and well-structured database. My aim was to make store management easier, faster, and more data-driven.
------
### 📌 Project Objectives

- Build a fully structured grocery store database with proper relationships.
- Store and manage customer, supplier, employee, product, and order information         efficiently.
- Track inventory levels and reduce stock-out issues.
- Generate useful sales and performance insights using SQL queries.
- Improve decision-making through data analysis.
- ------

### 🗂️ Database Schema

*My project consists of the following main tables:*

### 1. Customers:

- CustomerID
- Name
- Contact
- Email
- Address

### 2. Suppliers:

- SupplierID
- Name
- Contact
- Address

### 3. Employees:

- EmployeeID
- Name
- Role
- Contact

### 4. Categories:

- CategoryID
- CategoryName

### 5. Products:

- ProductID
- Name
- CategoryID
- SupplierID
- Price
- StockQty

### 6. Orders:

- OrderID
- CustomerID
- EmployeeID
- OrderDate
- TotalAmount

### 7. OrderDetails:

- OrderDetailID
- OrderID
- ProductID
- Quantity
- PriceEach

- The database uses primary keys, foreign keys, and relationships to maintain        consistency and integrity.
------

  ### 🛠️ Tools & Skills I Used :

- SQL (MySQL / PostgreSQL / SQLite)
- Database schema design
- Normalization & relationships
- Data insertion scripts
- Analytical SQL queries
- Joins, grouping, aggregates, subqueries, views
-----
### 📊 Key Insights I Found

- A small number of loyal customers contribute a large share of revenue.
- Best-selling items need consistent stock to avoid missed sales.
- Some products show low movement, indicating overstock risk.
- A few suppliers contribute the majority of inventory and revenue.
- Certain employees handle most orders, showing strong performance.

  ### 🚀 How to Run

#### 1. Install MySQL 8+ (or MariaDB).
#### 2. Create a new database for this project:

   CREATE DATABASE GROCERY_STORE;
USE GROCERY_STORE;
#### 3. Copy and run the script from GROCERY_STORE_PROJECT.sql (or your schema + insert file) into your SQL client.
- MySQL 8+ is recommended for best compatibility.

#### 4. Explore the queries step by step:
- Section A: Basic SQL filters (WHERE)
- Section B: Joins & Subqueries (Customers, Products, Orders, Suppliers)
- Section C: Aggregations & Grouping (GROUP BY, HAVING)
- Section D: Advanced SQL

  - CTEs
  - Window Functions
  - Views
  - Employee & Supplier Performance Queries
  - Revenue Analysis Queries
  
### ✅ Conclusion :

- This SQL project gave me practical experience in building a structured database and performing data analysis for a grocery store system. By working on schema design and analytical queries, I improved my technical skills and learned how SQL can support business insights and decision-making. This project plays an important role in my journey toward becoming a data analyst.
