# ECommerceDB - MySQL Project

This project contains the SQL schema and sample data for an **E-Commerce Database System**, created using **MySQL Workbench**. The database simulates an online shopping environment including customers, products, orders, payments, and business logic using views, procedures, triggers, and functions.

---

## 📄 Schema Overview

### Tables:
- `Customers`: Stores customer details
- `Products`: Contains product catalog with pricing and stock
- `Orders`: Tracks customer orders
- `OrderDetails`: Line items of products per order
- `Payments`: Records payment details for orders

---

## 📦 Features Implemented

- ✅ Data Insertion into all major tables
- ✅ Use of **Primary** and **Foreign Keys**
- ✅ `JOIN` queries for:
  - Order summary with payment status
  - Top-selling products
- ✅ `VIEW` named `OrderSummary` for consolidated order reports
- ✅ `STORED PROCEDURE` to fetch customer-wise order details
- ✅ `TRIGGER` to update product stock after an order
- ✅ `FUNCTION` to fetch live product stock by product ID

---

## 🧪 Sample Queries Included

- View all orders with customer & payment info
- Top-selling product report
- Orders containing multiple products
- Products with stock below a threshold

---

## 🚀 How to Use

1. Open `ECommerceDB.sql` in **MySQL Workbench**
2. Run the entire script (Ctrl + Shift + Enter or ⚡ button)
3. Explore tables, views, procedures, triggers, and functions

---


DROP DATABASE ECommerceDB;
