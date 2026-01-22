🛒 E-Commerce Backend 
A production-ready backend for an E-Commerce application built using Spring Boot and SQL database.
This backend manages Customers, Categories, Products, and Orders with RESTful APIs and clean architecture.
# 🛒 E-Commerce Backend API

A clean and scalable **E-Commerce backend application** built using **Spring Boot** and **SQL database**.  
This project provides REST APIs for managing **Customers, Categories, Products, and Orders**.

---

## 📌 Features

- Customer management
- Category management
- Product management
- Order creation and tracking
- SQL database integration
- RESTful API design
- Docker support

---

## 🧰 Tech Stack

- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA (Hibernate)  
- SQL Database (MySQL / PostgreSQL)  
- Maven  
- Docker  

---

## 🏗 Application Architecture



<img width="1380" height="1077" alt="Screenshot 2026-01-21 184430" src="https://github.com/user-attachments/assets/b7769eba-b006-45d6-b90e-9bec06893eb6" />

🚀 Tech Stack
Java 17
Spring Boot
Spring Web (REST APIs)
Spring Data JPA (Hibernate)
SQL Database (MySQL)
Thymleaf
Maven

📦 Core Modules
✅ Customer Management
Create & manage customers
Customer authentication (optional)
Customer order history
✅ Category Management
Create categories
Assign products to categories
Category-wise product listing
✅ Product Management
Add / update / delete products
Price, stock, images
Product-category mapping
✅ Order Management
Place orders
Order status (CREATED, PAID, SHIPPED, DELIVERED)
Order items & total calculation
🗄 Database Design (SQL)
Main Tables
customers
categories
products
orders
order_items
Relations:
One Category → Many Products
One Customer → Many Orders
One Order → Many Order Items
