<div align="center">

# 🏦 Banking System in C

### A Console-Based Banking Application

A C programming project that simulates basic banking operations, with transaction validation and file-based data persistence.

![Language](https://img.shields.io/badge/Language-C-A8B9CC?style=for-the-badge\&logo=c\&logoColor=white)
![Compiler](https://img.shields.io/badge/Compiler-GCC-6C8EBF?style=for-the-badge\&logo=gnu\&logoColor=white)
![Project Type](https://img.shields.io/badge/Project-Console_Application-8A63D2?style=for-the-badge)

</div>

---

## 📌 About the Project

The **Banking System** is a menu-driven C application that simulates essential banking transactions through a console interface.

Users can deposit money, withdraw funds, and check their account balance. The application also demonstrates transaction validation and file handling to preserve account information between program sessions.

This project applies fundamental C programming concepts to a practical financial simulation.

> **Disclaimer:** This project is intended for educational purposes only. It is not a real banking application and should not be used to store or manage actual financial information.

---

## ✨ Features

* 💰 **Deposit:** Add money to the account.
* 💸 **Withdrawal:** Withdraw funds while checking the available balance.
* 📊 **Balance Enquiry:** View the current account balance.
* 🛡️ **Transaction Validation:** Reject invalid transaction amounts.
* ⚖️ **Insufficient Balance Protection:** Prevent withdrawals that exceed available funds.
* 💾 **File-Based Persistence:** Preserve account information between sessions.

---

## 🧠 Concepts Demonstrated

| Concept                | Application                                       |
| :--------------------- | :------------------------------------------------ |
| Functions              | Organize banking operations into manageable units |
| Conditional statements | Control transaction logic                         |
| Loops                  | Support repeated menu interactions                |
| Input validation       | Check transaction amounts                         |
| File handling          | Save and retrieve account information             |
| Arithmetic operations  | Calculate deposits, withdrawals, and balances     |

---

## 🛠️ Technology Stack

* **Language:** C
* **Compiler:** GCC
* **Interface:** Command-line / console
* **Data storage:** File-based persistence

---

## ⚙️ Getting Started

### Prerequisites

* GCC compiler installed and available in your terminal.
* Git installed to clone the repository.

### 1. Clone the repository

```bash id="1g0qrf"
git clone https://github.com/ballsohini939-alt/banking-system-c.git
```

### 2. Enter the project directory

```bash id="cn8v9v"
cd banking-system-c
```

### 3. Compile the program

If the source file is named `banking_system.c`, run:

```bash id="v5qcnq"
gcc banking_system.c -o banking_system.exe
```

### 4. Run the program

In Windows PowerShell:

```powershell id="xv7ckj"
.\banking_system.exe
```

**Note:** If your source file has a different name, replace `banking_system.c` with the actual filename in the compilation command.

---

## 🔐 Transaction Validation

The application demonstrates basic safeguards for simulated banking transactions, including:

* Rejecting invalid transaction amounts.
* Preventing withdrawals that exceed the available balance.
* Updating the balance after successful transactions.

These checks demonstrate basic application logic. They do not provide the security, authentication, audit logging, or financial safeguards required by real banking systems.

---

## 💾 Data Persistence

The program uses file handling to preserve account information between sessions.

Keep the generated account data file if you want to retain the saved information. Avoid deleting or overwriting it unintentionally.

---

## 🧪 What This Project Helps Practice

* Building interactive, menu-driven applications.
* Implementing transaction-related logic.
* Validating user input.
* Working with file-based data persistence.
* Testing edge cases, such as invalid amounts and insufficient funds.
* Organizing C code into manageable functions.

---

## 🚀 Future Improvements

Potential enhancements include:

* Supporting multiple customer accounts.
* Adding transaction history.
* Implementing account authentication.
* Improving error handling and input validation.
* Adding transaction summaries and reports.

---

## 👩‍💻 Author

**Sohini Ball**
B.Tech Computer Science and Engineering Student

Interested in software development, problem-solving, and building practical applications.

**GitHub:** [@ballsohini939-alt](https://github.com/ballsohini939-alt)

---

<div align="center">

*Learn · Build · Test · Improve*

</div>
