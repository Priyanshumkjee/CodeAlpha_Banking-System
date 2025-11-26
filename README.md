# CodeAlpha_Banking-System
🏦 Bank Management System (C++)

A fully functional console-based Bank Record Management System built using C++.
This project provides account creation, record modification, deposits, withdrawals, balance inquiry and complete management of bank user data using file handling.

This program stores account details in binary format ensuring data persistence even after program closure.
Source reference from code: account handling, creation, modification, deposit/withdraw, and file management 

Bank_Management

✨ Features
Feature	Description
🆕 Create New Bank Account	Add user details including name, account type and initial balance
✏ Modify Existing Account	Update account holder details, type and stored balance
💰 Deposit Amount	Add balance to an existing account
💸 Withdraw Money	Safe withdrawal with minimum balance check
🔍 Account Balance Inquiry	View full details of a specific account
📋 All Account Listing	Display a table of all stored bank accounts
❌ Delete Account	Remove an account record permanently
💾 Persistent Storage	Data is stored in account.dat file using binary I/O
📂 Project Structure
📁 Bank-Management-System
│── Bank_Management.cpp   # Main Source Code
│── account.dat           # Auto-generated binary storage file
│── README.md             # Documentation

🧠 How It Works

The project uses Object-Oriented Programming + File Handling in C++.

🔸 Class Bank includes:
Function	Purpose
Get_Data()	Create new account
Write_Data()	Save account to file
Display_Invidual_Records()	Show a specific account
report()	Display user list format
dep() / draw()	Add or deduct amount
Modification_data()	Modify account info
retacno() / rettype() / retdeposit()	Data access methods
🔸 Other Key Functions:
Get_All_Data();          // Show all accounts
Deposit_Withdraw();      // Deposit or withdraw balance
Account_Modification();  // Update stored data
Delete_Account();        // Remove account file entry


All operations use binary read/write through fstream, enabling persistent storage even after exit 

Bank_Management

.

▶ Running the Program
1. Clone the repository
git clone https://github.com/Priyanshumkjee/ CodeAlpha_Banking-System
cd Bank-Management-System

2. Compile
g++ Bank_Management.cpp -o bank_system

3. Run
./bank_system

🖥 Menu Preview
===========================
   BANKING RECORD SYSTEM
===========================

01. CREATE NEW ACCOUNT
02. MODIFY AN ACCOUNT
03. BALANCE ENQUIRY
04. DEPOSIT
05. WITHDRAW
06. ALL ACCOUNT HOLDER LIST
07. CLOSE AN ACCOUNT
08. EXIT

🔐 Constraints Implemented

✔ Minimum Balance

Saving: ₹500

Current: ₹1000

✔ Max Deposit Allowed: ₹10,00,000
✔ Account Number strictly 12 digits

All validations present in code logic 

Bank_Management

.

👨‍💻 Developer

Created By: Abhisht Chouhan
Written fully in C++ with file-based record storage.

⭐ Support the Project

If you like this project:

💠 Star the repository
🔄 Fork & improve it
🐛 Submit issues & suggestions
