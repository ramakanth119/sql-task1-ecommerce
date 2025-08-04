# sql-task1-ecommerce
SQL internship task: E-commerce database schema
# 📦 E-commerce Database Schema – Task 1

## 📁 Internship: SQL Developer - Task 1

### 📚 Domain: E-commerce

This project models an e-commerce system using SQL. It defines a normalized relational database schema for managing customers, products, orders, payments, and shipping.

---

### 🧱 Tables:
- `Customers`
- `Categories`
- `Products`
- `Orders`
- `Order_Items`
- `Payments`
- `Shipping`

---

### 🔗 Relationships:
- One customer → many orders
- One order → many products (via `Order_Items`)
- One product → one category
- One order → one payment, one shipping

---

### ⚙️ Tools Used:
- MySQL Workbench
- dbdiagram.io
- GitHub

---

### 📦 Files in this Repo:
- `ecommerce_schema.sql` – SQL script
- `Ecommerce_Database_Task1.pdf` – Task report
- *(Optional)* `er_diagram.png` – Visual ER diagram

---

### ✅ Author:
Ramakanth Devineni
