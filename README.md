Bookstore Analysis Using SQL

Project Overview

The Bookstore Analysis project focuses on analyzing book sales, inventory, pricing, customer locations, and revenue using SQL. The project uses a relational database to explore bookstore performance and generate meaningful business insights.

Project Objectives

* Analyze book sales and revenue.
* Identify popular book categories and authors.
* Analyze customer purchasing patterns across cities.
* Evaluate book prices and available stock.
* Generate insights to support business decisions.

Tech Stack

* Database: MySQL
* Language: SQL
* Tool: MySQL Workbench

Database Structure

The project uses a database named bookstore_db2 with two tables:

1. Books

Contains book and inventory information.

| Column    | Description             |
| --------- | ----------------------- |
| book_id   | Unique ID for each book |
| title     | Book title              |
| author    | Book author             |
| category  | Book category           |
| price     | Book price              |
| publisher | Publisher name          |
| stock     | Available stock         |

2. Sales

Contains customer sales transaction information.

| Column        | Description             |
| ------------- | ----------------------- |
| sale_id       | Unique ID for each sale |
| book_id       | ID of the book sold     |
| customer_name | Customer name           |
| customer_city | Customer's city         |
| sale_date     | Date of sale            |
| quantity      | Number of books sold    |
| total_amount  | Total sale amount       |

The book_id column connects the Books and Sales tables through a foreign key relationship.

Key Analysis Areas

* Total sales and revenue analysis
* Book category performance
* Author-wise sales analysis
* City-wise customer sales
* Book pricing analysis
* Inventory and stock analysis
* Sales trends over time
* Quantity of books sold

Business Benefits

* Helps identify high-performing book categories.
* Supports inventory and stock management.
* Provides insights into customer locations and purchasing behavior.
* Helps evaluate sales performance and revenue.
* Supports data-driven business decisions.

Skills Demonstrated

* SQL
* MySQL
* Database Design
* Table Relationships
* Data Analysis
* Sales and Revenue Analysis
* Inventory Analysis
* Business Insights

Conclusion

This project demonstrates how SQL can be used to analyze bookstore sales, customer locations, book categories, pricing, and inventory. It showcases practical SQL skills and the use of data to support business analysis.
