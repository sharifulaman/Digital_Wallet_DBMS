# 💳 Digital Wallet System

## 📘 Project Overview

The **Digital Wallet System** is a relational database design for a digital wallet application. It manages user accounts, wallets, transactions, linked bank accounts, bill payments, and authentication logs. This system ensures secure, efficient, and scalable financial operations.

---

## ✅ Features

- **User Management**: Stores user info (full name, NID, mobile, email, PIN, user type).
- **Wallet Management**: Tracks user wallet balances.
- **Transaction Processing**: Supports SendMoney, CashIn, CashOut, Payment, and ReceiveMoney transactions with status tracking.
- **Bank Account Integration**: Manages user-linked bank accounts with verification status.
- **Bill Payments**: Facilitates electricity, water, internet, and tuition bill payments.
- **Authentication Logs**: Records login attempts with success/failure indicators.
- **Database Design**: Six normalized tables with integrity constraints.

---

## 🛠 Technologies Used

- **Database**: SQL (MySQL, PostgreSQL, etc.)
- **Data Modeling**: Normalized schema with PK/FK constraints
- **ENUM Types**: Used for transaction types, user types, bill types
- **Diagram Tools**: MySQL Workbench, Lucidchart, dbdiagram.io

---

## 📁 Project Structure

