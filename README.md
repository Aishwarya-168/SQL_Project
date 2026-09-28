# SQL Project

A collection of two SQL database projects that demonstrate database design, data manipulation, and analytical querying using SQL.

| # | Project | Domain |
|---|---------|--------|
| 1 | [Online Bookstore](#1-online-bookstore) | E-commerce / Retail |
| 2 | [Retailer Operations](#2-retailer-operations) | Retail / Business Operations |

---

## Repository Structure

```
SQL_Project/
│
├── onlinebookstore/
│   ├── (schema / table creation scripts)
│   ├── (data insertion scripts)
│   └── (analysis queries)
│
├── retailer_operators/
│   ├── (schema / table creation scripts)
│   ├── (data insertion scripts)
│   └── (analysis queries)
│
└── README.md
```

> Update the file names above to match the files in your folders.

---

## 1. Online Bookstore

A relational database for an online bookstore that manages books, customers, and orders.

### Objectives
- Design a normalized database for an online book-selling business
- Store and manage book, customer, and order information
- Answer business questions using SQL queries

### Typical Tables
- **Books**: title, author, genre, price, stock
- **Customers**: name, email, city, country
- **Orders**: order date, quantity, total amount, linked customer and book

### Concepts Covered
- `CREATE TABLE`, primary keys, foreign keys
- `INSERT`, `UPDATE`, `DELETE`
- `SELECT` with `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`
- Aggregate functions: `SUM`, `COUNT`, `AVG`, `MAX`, `MIN`
- `JOIN`s across multiple tables
- Subqueries

### Sample Questions Answered
- Which books are the best sellers?
- Which customers have spent the most?
- What is the total revenue by genre?
- Which books are low in stock?
- How many orders were placed each month?

---

## 2. Retailer Operations

A relational database that models day-to-day retail operations such as products, suppliers, sales, and inventory.

### Objectives
- Model core retail business operations in a structured database
- Track products, sales, and stock levels
- Generate insights to support business decisions

### Typical Tables
- **Products**: name, category, price, stock quantity
- **Suppliers / Retailers**: contact and location details
- **Sales / Orders**: transactions, dates, quantities, amounts

### Concepts Covered
- Database and table design with constraints
- Data filtering, sorting, and grouping
- Multi-table `JOIN`s
- Aggregations and reporting queries
- Subqueries and (optionally) views, window functions, and CTEs

### Sample Questions Answered
- Which products generate the most revenue?
- Which retailers or suppliers contribute the most sales?
- What is the sales trend over time?
- Which items need restocking?

---

## Tools & Technologies

- **Language:** SQL
- **Database:** MySQL *(change if you used PostgreSQL, SQL Server, etc.)*
- **Tools:** MySQL Workbench / any SQL client, Git & GitHub

---

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aishwarya-168/SQL_Project.git
   cd SQL_Project
   ```

2. **Open your SQL client** (e.g., MySQL Workbench).

3. **Run the scripts in order** for the project you want to explore:
   1. Create the database and tables
   2. Insert the sample data
   3. Run the analysis queries

4. Repeat for the second project.

---

## Key Learnings

- Designing relational schemas with proper keys and relationships
- Writing efficient queries for real-world business questions
- Using joins, aggregations, and subqueries to extract insights

---

## Author

**Aishwarya**
GitHub: [@Aishwarya-168](https://github.com/Aishwarya-168)

---

⭐ If you found this repository helpful, consider giving it a star!
