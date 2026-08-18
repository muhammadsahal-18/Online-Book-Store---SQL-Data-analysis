# Online-Book-Store SQL-Data-analysis
📚 Online Book Store — SQL Data Analysis

🗄️ SQL & MySQL Data Analysis Project

A SQL data analysis project focused on analyzing an online bookstore using SQL and MySQL.

The project works with Books, Customers, and Orders datasets to analyze sales, revenue, customer purchasing behavior, popular books, genre-wise performance, and inventory levels.

---

🎯 Project Objective

The main objective is to use SQL queries to extract meaningful information from bookstore data and understand sales and customer behavior.

The analysis focuses on:

- Total sales
- Revenue
- Popular books
- Customer purchase patterns
- Genre-wise sales
- High-value customers
- Book demand
- Inventory levels

---

🛠️ Tools & Technologies

Technology| Purpose
🗄️ SQL| Data analysis
🐬 MySQL| Database management
🔗 JOIN| Combining related datasets
📊 GROUP BY| Group-level analysis
🔎 HAVING| Filtering aggregated results
➕ Aggregate Functions| Sales and revenue calculations
🔍 Subqueries| Advanced data analysis

---

📂 Datasets

The project uses three main datasets:

📚 Books

Contains information about books and their availability.

👥 Customers

Contains customer information used for purchase and customer analysis.

🛒 Orders

Contains order information used to analyze sales and customer purchasing behavior.

---

🔄 Project Workflow

Books Dataset
      +
Customers Dataset
      +
Orders Dataset
      ↓
MySQL Database
      ↓
SQL Queries
      ↓
Data Analysis
      ↓
Business Insights

---

🔍 SQL Analysis

💰 Sales & Revenue Analysis

Used SQL queries to identify:

- Total sales
- Revenue
- Sales performance
- Order-level information

📚 Popular Books

Analyzed book demand to identify books with higher sales and purchase quantities.

👥 Customer Analysis

Analyzed customer purchasing patterns and identified high-value customers.

🎭 Genre Analysis

Compared sales across different genres to understand genre-wise performance.

📦 Inventory Analysis

Compared available stock with quantities sold to evaluate inventory levels.

---

🧠 SQL Concepts Demonstrated

SELECT
WHERE
JOIN
GROUP BY
HAVING
ORDER BY
Aggregate Functions
Subqueries

---

📊 Example Query

SELECT
    b.title,
    SUM(o.quantity) AS total_quantity
FROM books b
JOIN orders o
    ON b.book_id = o.book_id
GROUP BY b.title
ORDER BY total_quantity DESC;

This query can be used to analyze book demand based on total quantity ordered.

---

🖼️ SQL Results

Add screenshots of your MySQL query results here:

![SQL Analysis](screenshots/sql-results.png)

---

💡 Key Skills Demonstrated

- SQL Query Writing
- MySQL
- Database Analysis
- Data Extraction
- Joins
- GROUP BY
- HAVING
- Aggregate Functions
- Subqueries
- Sales Analysis
- Customer Analysis
- Inventory Analysis

---

📁 Project Structure

online-book-store-sql-analysis/
│
├── README.md
│
├── database/
│   └── bookstore.sql
│
├── queries/
│   ├── sales_analysis.sql
│   ├── customer_analysis.sql
│   ├── book_analysis.sql
│   └── inventory_analysis.sql
│
└── screenshots/
    └── sql-results.png

---

👤 Author

Muhammad Sahal

Aspiring Data Analyst

Skills: SQL • Excel • Power BI • Python • Data Visualization

🔗 LinkedIn: linkedin.com/in/muhammad-sahal-2bb6a938

🌐 Portfolio: datascienceportfol.io/MhdSahal18
