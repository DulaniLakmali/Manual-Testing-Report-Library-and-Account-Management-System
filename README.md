# 📚 Library and Account Management System (LMS + AMS)

A full-featured system for managing library users, book borrowing, account creation, fund transactions, and loan applications — tested and validated through **manual software testing** as part of an **SQ intern project**.

---

## 🌟 Project Overview

The **Library and Account Management System** is a modular application designed to manage:

* 📘 Library users and book borrowing
* 👤 User account creation and updates
* 💸 Deposits, withdrawals, and fund transfers
* 🧾 Loan applications and eligibility checking

As part of the **Software Quality Assurance internship**, I conducted comprehensive **manual testing** across all modules to verify functional correctness, data integrity, and proper error handling.

---

## ✅ Modules Covered

### 🔐 Account Management

* Create, update, and delete user accounts
* Handle missing or invalid input validation
* View and modify account contact details

### 💰 Transaction Management

* Deposit and withdraw funds with balance updates
* Handle edge cases like insufficient funds

### 🔄 Fund Transfers

* Transfer funds between users/accounts
* Detect invalid accounts or low balance scenarios

### 🏦 Loan Management

* Apply for loans with eligibility criteria
* Display relevant success or rejection messages

### 📚 Library Management

* Register users with different roles (Admin, Student, etc.)
* Update user profiles with new contact info
* Search books by title or author
* Borrow and return books with real-time status updates

---

## 🧪 Manual Testing Highlights

| Module                  | Test Cases | Status      |
| ----------------------- | ---------- | ----------- |
| Account Management      | 4          | ✅ Pass      |
| Transaction Management  | 3          | ✅ Pass      |
| Fund Transfers          | 3          | ✅ Pass      |
| Loan Management         | 3          | ✅ Pass      |
| User Management (LMS)   | 3          | ✅ Pass      |
| Book Search & Borrowing | 4          | ✅ Pass      |
| **Total**               | **20**     | ✅ 100% Pass |

> 💡 All test cases were executed manually using black-box testing techniques. Each scenario was validated by comparing actual vs expected results and documented clearly in test logs.

---

## 📋 Sample Test Scenario (Example)

```markdown
**Test Scenario:** Borrow an available book  
**Test Case ID:** BB-01  
**Test Steps:**  
1. Select an available book  
2. Click "Borrow"  
**Expected Result:**  
- Book status updated to "Checked Out"  
- User's borrowing record updated  
**Actual Result:**  
- Status changed as expected, and record updated  
**Status:** Pass ✅
```

---

## 🛠️ Tools & Techniques

* ✔️ Manual Testing (Black-box approach)
* 🧾 Test Case Documentation
* 🧪 Functional Testing
* 🔍 Input Validation Testing
* ⏱️ Response Time Monitoring (for search features)

---

## 🎯 Key Learnings

* Understanding real-world manual testing process
* Writing clear and traceable test cases
* Error handling and validation testing
* Importance of user-centric quality assurance

---

## 📄 Documentation

You can find the full testing report (PDF) [here](#) *(link to your PDF or project repo)*.

---

## 🚀 Future Enhancements

* ✅ Automation testing with Selenium or Cypress
* 📈 Load testing for concurrent book searches
* 🔐 Role-based access control and security testing
* 📊 Dashboard for tracking loan and transaction analytics

