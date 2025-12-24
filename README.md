# 🏧 ATM Banking System – Console Application (C++)

A **console-based ATM simulation system** built using **C++**, designed to mimic real ATM operations such as login, withdrawals, deposits, and balance checking.

This project focuses on **client-side banking logic**, file handling, validation, and menu-driven interaction.

---

## 📌 Project Overview

The ATM system allows bank clients to securely log in using an **Account Number & PIN**, then perform common ATM operations while maintaining data persistence using text files.

All changes are saved immediately, simulating a real ATM connected to a banking backend.

---

## 🏗️ System Design

- Console-based interface
- Menu-driven navigation
- File-based data storage
- Client authentication system
- Real-time balance updates

---

## 🔐 Authentication

- Login using:
  - Account Number
  - PIN Code
- Credentials validated against stored client records
- Prevents access with invalid credentials

---

## 🚀 Main Features

### 💳 Client Operations
- Secure login
- Check account balance
- Logout and re-login

### 💰 Withdraw Options
#### ⚡ Quick Withdraw
- Predefined amounts:
  - 20, 50, 100, 200, 400, 600, 800, 1000
- Automatic balance validation
- Fast ATM-style experience

#### 🧾 Normal Withdraw
- Custom amount input
- Amount must be a multiple of 5
- Balance validation enforced

### ➕ Deposit
- Deposit any positive amount
- Immediate balance update
- Stored persistently in file

---

## 📂 File Handling

- Clients stored in `Clients.txt`
- Custom record format using separators (`#//#`)
- Load, update, and save client data safely
- Persistent balance updates after each transaction

---

## 🛠️ Technologies Used

- C++
- STL (`vector`, `string`, `fstream`, `iomanip`)
- File I/O
- Console UI
- Structured Programming

---

## 🧠 Concepts Applied

- Structs & Enums
- File-based persistence
- Input validation
- Defensive programming
- Menu-driven system design
- Real-world ATM logic simulation

---

## 📂 Project Structure
ATM Banking System
├── main.cpp
├── Clients.txt
├── Project Files (.vcxproj, .sln)
└── x64/

---

## ▶️ How to Run

1. Open the project in **Visual Studio**
2. Build the solution
3. Run the program
4. Login using a valid account number & PIN
5. Use menu options to perform ATM operations

---

## 🎯 Purpose of the Project

This project was built to:
- Practice real-world banking logic
- Strengthen C++ fundamentals
- Learn file-based data storage
- Simulate ATM workflows
- Build a strong console-based portfolio project

---

## ⚠️ Notes

- Educational project
- Data stored in plain text files
- PIN codes are not encrypted (learning purpose)
- Can be extended with:
  - PIN encryption
  - Daily withdrawal limits
  - Transaction history
  - GUI version

---

## 👤 Author

**Adnan Ghiyath**  
Self-taught Software Developer  
Focused on C++ & System Logic  
📍 UAE | 🇸🇾 Syrian

