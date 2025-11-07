# 🏦 Banking System (Pure Java)

A console-based **Banking Management System** built using **Core Java**, demonstrating strong **OOP principles**, **collections framework**, and **layered architecture**.

---

## 🚀 Features

- **Account Management:** Open, close, and view multiple accounts  
- **Deposit & Withdrawal:** Perform secure transactions with validation  
- **Fund Transfer:** Transfer funds between accounts instantly  
- **Transaction History:** View all past transactions with timestamps  
- **Statement Generation:** Generate detailed account statements  
- **Search & Filter:** Easily find accounts or transactions  
- **Custom Exception Handling:** Gracefully handles invalid inputs  
- **Data Validation:** Ensures clean, error-free user input  

---

## 🧩 Concepts & Technologies Used

- ✅ **Core Java (OOP Concepts — Encapsulation, Abstraction)**  
- ✅ **Java Records** for clean and immutable data representation  
- ✅ **Collections Framework (ArrayList, HashMap)**  
- ✅ **Custom Exception Classes & Validation Utilities**  
- ✅ **Repository Pattern** for data management  
- ✅ **Service Layer** for business logic  
- ✅ **Scanner** for user input  
- ✅ **LocalDateTime** for transaction timestamps  

---

## 🏗️ Project Architecture

src/
┣ 📂 model/ # Contains Java Records (Account, Transaction)
┣ 📂 repository/ # In-memory data management (AccountRepository)
┣ 📂 service/ # Business logic (BankService)
┣ 📂 exceptions/ # Custom exceptions (InvalidAccountException, etc.)
┣ 📂 utils/ # Validation helpers
┣ 📂 main/ # Entry point (Main.java)

Welcome to Simple Banking System
1. Open Account
2. Deposit
3. Withdraw
4. Transfer
5. View Transactions
6. Exit

Enter your choice: 1
Enter Name: John Doe
Account Created Successfully! Account ID: ACC1001
