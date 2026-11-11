# PLP Week 6 Assignment: SQL Joins and Relationships

## 📌 Assignment Overview

This assignment focuses on understanding and implementing SQL JOIN operations in MySQL. It demonstrates how to retrieve and combine related information from multiple tables using INNER JOIN, LEFT JOIN, and RIGHT JOIN.

## 🎯 Learning Objectives

By completing this assignment, I have practised how to:

- Understand and implement INNER JOIN, LEFT JOIN, and RIGHT JOIN.
- Retrieve information from multiple related database tables.
- Identify relationships between tables using common columns.
- Apply SQL joins to solve real-world database problems.

## 🛠️ Tools and Technologies

- **Database:** MySQL
- **Database:** Classic Models
- **SQL Editor:** MySQL Workbench
- **Code Editor:** Visual Studio Code
- **Version Control:** Git and GitHub

## 📚 Assignment Questions

### Question 1: INNER JOIN – Employees and Offices

Retrieved employee information, including:

- firstName
- lastName
- email
- officeCode

Used INNER JOIN to combine the `employees` and `offices` tables through the `officeCode` column.

### Question 2: LEFT JOIN – Products and Product Lines

Retrieved product information, including:

- productName
- productVendor
- productLine

Used LEFT JOIN to combine the `products` and `productlines` tables through the `productLine` column.

### Question 3: RIGHT JOIN – Customers and Orders

Retrieved order information, including:

- orderDate
- shippedDate
- status
- customerNumber

Used RIGHT JOIN to combine the `customers` and `orders` tables through the `customerNumber` column. The query returns the first 10 orders.

## 📂 Repository Structure

```text
week6-sql-joins/
│
├── answer.sql
└── README.md
```

## ▶️ How to Run the SQL Queries

1. Install and open MySQL Workbench.
2. Import or select the Classic Models database.
3. Open the `answer.sql` file.
4. Select the `classicmodels` database:

```sql
USE classicmodels;
```

5. Execute the SQL queries individually or together.
6. Review the results in the MySQL Workbench output grid.

## 📖 Key Concepts Learned

- **INNER JOIN:** Retrieves records with matching values in both tables.
- **LEFT JOIN:** Returns all records from the left table and matching records from the right table.
- **RIGHT JOIN:** Returns all records from the right table and matching records from the left table.
- **ON:** Specifies the condition used to connect related tables.
- **ORDER BY:** Sorts query results.
- **LIMIT:** Restricts the number of returned records.

## 👩‍💻 Author

**Farah Salat Mohamed**

PLP Digital Skilling Programme

Week 6 – Database Systems Assignment

---

*This assignment demonstrates practical understanding of SQL joins and relationships using the MySQL Classic Models database.*
