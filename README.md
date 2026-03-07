# 🏦 Banking Management System

A console-based Banking Management System developed using **Java**, **JDBC**, and **MySQL**.  
This project demonstrates real-world banking operations with secure transaction handling and database connectivity.

---

## 🚀 Project Overview

This application allows users to:

- Register and Login securely
- Create Bank Accounts
- Credit Money
- Debit Money
- Transfer Money between accounts
- Check Account Balance
- Validate transactions using Security PIN
- Prevent SQL Injection using PreparedStatement

---

## 🛠 Technologies Used

- Java
- JDBC (Java Database Connectivity)
- MySQL
- Eclipse IDE
- Git & GitHub

---

## 📂 Project Structure
BankingManagementSystem
│
├── src/
│ ├── AccountManager.java
│ ├── Accounts.java
│ ├── BankingApp.java
│ ├── User.java
│
├── .gitignore
├── .project
├── .classpath


---

## 🗄 Database Setup

### 1️⃣ Create Database


CREATE DATABASE banking_system;
USE banking_system;

- ▶️ How to Run the Project
- 1️⃣ Clone the Repository
- git clone https://github.com/your-username/BankingManagementSystem.git
- 2️⃣ Open in Eclipse

- Import as Existing Java Project.

- 3️⃣ Update Database Credentials

- Inside your connection class:

- String url = "jdbc:mysql://localhost:3306/banking_system";
- String username = "root";
- String password = "your_password";

- 4️⃣ Run the Application

- Run:
- BankingApp.java

🔐 Key Features

- ✔ Secure Login System
- ✔ Account Number Auto-Generation
- ✔ Money Credit & Debit
- ✔ Fund Transfer Between Accounts
- ✔ Balance Inquiry
- ✔ Security PIN Validation
- ✔ SQL Injection Protection
- ✔ Transaction Handling using JDBC

📸 Sample Console Output
- *** WELCOME TO BANKING SYSTEM ***

 1. Register
 2. Login
 3. Exit

Enter your choice:
🎯 Learning Outcomes

Practical JDBC implementation

Database Transactions

PreparedStatement usage

Real-world backend project structure

Git version control


⭐ If you found this project helpful, consider giving it a star!


