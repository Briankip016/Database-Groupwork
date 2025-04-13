# Database-Groupwork

# 📚 Bookstore SQL Database Project

This project is a fully designed and implemented **MySQL relational database** for managing the operations of a bookstore. It was created to practice real-world database design, normalization, user access control, and SQL queries.

---

## 🚀 Project Overview

The goal of this project is to create a relational database system that stores and manages data for a bookstore, including books, authors, customers, orders, and shipping details. The database supports multiple operations like CRUD (Create, Read, Update, Delete), tracking order history, and managing multiple addresses per customer.

---

## 🧱 Database Structure

This system includes **15 interconnected tables**:

- `book`
- `author`
- `book_author` (many-to-many relation)
- `book_language`
- `publisher`
- `customer`
- `address`
- `address_status`
- `country`
- `customer_address`
- `cust_order`
- `order_line`
- `shipping_method`
- `order_status`
- `order_history`

---

## 🛠️ Technologies Used

- **MySQL 8.0+**
- **MySQL Workbench**
- **Draw.io** (for ERD design)
- **Git & GitHub** (for version control)

---

## 🔐 User Roles & Access Control

We created three users with different roles:

| User              | Role Description                            |
|-------------------|---------------------------------------------|
| `bookstore_admin` | Full access to manage database and users     |
| `bookstore_editor` | Can read, insert, update, and delete data   |
| `bookstore_reader` | Read-only access for querying data          |

---

## 📥 Sample Data

Sample records were inserted into all tables to simulate real bookstore operations including:

- Books with prices, publishers, and authors
- Customers with multiple addresses
- Orders with statuses and shipping methods
- Order history to track status updates

---

## 📄 Example Queries

- Join books with authors and publishers
- Track order status by customer
- View books in each order
- Get customer addresses by status

---

## ✅ How to Run

1. Clone this repository
2. Open MySQL Workbench
3. Run the `CREATE DATABASE` and `CREATE TABLE` scripts
4. Insert sample data (`INSERT INTO ...`)
5. Test queries and create views

---

## 🙌 Contributors

- 1.⁠ ⁠Brian Kipkorir - briankipkorir016@gmail.com
- 2.⁠ ⁠Moses parsele - leyianmoses126@gmail.com
- 3.⁠ ⁠Sinetemba Xhosa - xsinetemba@gmail.com

---
