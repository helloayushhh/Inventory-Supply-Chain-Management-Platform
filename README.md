# 📦 Inventory Management & Sales Tracking System

A Java-based desktop application designed to simplify inventory operations by managing products, suppliers, customers, purchases, sales, and stock availability from a centralized system.

The application helps businesses maintain accurate inventory records, track transactions, and monitor stock levels through an intuitive interface backed by a MySQL database.

---

## 🚀 Features

### Product Management

* Add, update, delete, and search products
* Maintain product inventory records
* Monitor current stock availability

### Supplier Management

* Add and manage supplier information
* Track supplier-related purchase records

### Customer Management

* Store and manage customer details
* Associate customers with sales transactions

### Purchase Management

* Record product purchases
* Automatically update inventory stock

### Sales Management

* Process product sales
* Maintain sales transaction history
* Update stock levels after each sale

### Reporting

* Generate sales reports
* View business transaction records

### User Management

* Support for multiple user roles
* Administrator access for managing users and reports

---

## 👥 User Roles

### Administrator

* Manage products, suppliers, customers, purchases, and sales
* View sales reports
* Create and manage system users

### Normal User

* Manage products, suppliers, customers, purchases, and sales
* Access inventory operations
* Restricted from user management and reporting features

---

## 🛠️ Technology Stack

* Java SE
* MySQL
* JDBC
* Java Swing
* JCalendar
* JTattoo
* SQLConnector

---

## 📂 Project Structure

The system maintains and manages:

* Product Records
* Supplier Records
* Customer Records
* Purchase Transactions
* Sales Transactions
* Inventory Stock Information
* User Accounts

---

## ⚙️ Setup Instructions

### 1. Configure MySQL

Ensure MySQL is installed and running.

Default database credentials:

```text
Username: root
Password: root
```

If your credentials are different, update them in:

```text
ims/src/com/inventory/database/ConnectionFactory.java
```

### 2. Import Database

Download and import the SQL file into MySQL:

https://drive.google.com/file/d/0Bw-qNYNSGhdCN09YZDV6SmtRN00/view?usp=sharing&resourcekey=0-g98Gi5ErSgzV-Jit-4Ow6Q

### 3. Install Required Libraries

Download the required third-party plugins:

https://drive.google.com/file/d/0Bw-qNYNSGhdCMU1mekN4SmRCb1E/view?usp=sharing&resourcekey=0-mynFCWwHM0l7oUuBwDIVbw

Included libraries:

* JCalendar
* JTattoo
* SQLConnector

### 4. Run the Application

* Import the project into your preferred Java IDE
* Add the required libraries
* Configure database credentials if necessary
* Build and run the project

---

## 🔑 Demo Credentials

Use the following credentials after database setup:

```text
Username: user4
Password: test123
```

---

## 📈 Future Enhancements

* Advanced inventory analytics
* Export reports to PDF and Excel
* Enhanced role-based access control
* Cloud database integration
* Inventory alerts and notifications
* Web-based version of the application

---

## 📋 Key Highlights

* Inventory and stock management
* Purchase and sales tracking
* Supplier and customer management
* Role-based user access
* MySQL-backed data persistence
* Desktop application built with Java SE

This project demonstrates practical application of object-oriented programming, database management, transaction handling, user authentication, and desktop application development using Java and MySQL.
