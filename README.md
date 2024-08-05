# 🏦 **BankXcellence**

**BankXcellence** is a comprehensive bank management system designed to handle various banking operations efficiently. This console-based application provides functionalities for managing customer accounts, including creating accounts, depositing and withdrawing money, and modifying or deleting records.

## 📋 **Features**

### **For Users:**
- **Create a New Account:** Easily set up a new account with initial deposit and account type selection.
- **Deposit Funds:** Add funds to your account.
- **Withdraw Funds:** Remove funds from your account with balance checks.
- **Balance Inquiry:** Check the current balance of your account.
- **Modify Account Details:** Update personal information and account details.
- **Delete Account:** Remove an account from the system.
- **View All Accounts:** Display a list of all accounts with their details.

### **For Administrators:**
- **Manage Accounts:** Access functionalities to create, modify, and delete accounts.
- **View Account Details:** Retrieve and review account information as needed.

## 🛠️ **Tools & Technologies**

The project utilizes various tools and technologies for development:
- **C++**: The primary programming language used for implementing the application.
- **File I/O**: For handling data storage and retrieval operations.

## 📁 **Source Code Overview**

### **Header Files:**
- `iostream` – For input and output operations.
- `fstream` – For file operations.
- `cctype` – For character handling functions.
- `iomanip` – For input and output formatting.

### **Classes:**
- **`account`**: The core class for managing account data, including:
  - **Member Functions:**
    - `create_account()`
    - `show_account()`
    - `modify()`
    - `dep(int)`
    - `draw(int)`
    - `report()`
    - `retacno()`
    - `retdeposit()`
    - `rettype()`

### **Main Functions:**
- `write_account()`
- `display_sp(int)`
- `modify_account(int)`
- `delete_account(int)`
- `display_all()`
- `deposit_withdraw(int, int)`
- `intro()`

## 📂 **Files and Data Storage**

- **Data File**: `account.dat` – Stores account information in binary format.
- **Temporary File**: `Temp.dat` – Used for deleting records.

## 📑 **Usage Instructions**

1. **Compile and Run:** Compile the `BankXcellence` project using a C++ compiler and run the executable.
2. **Main Menu:** Follow the on-screen menu to perform banking operations:
   - `01. NEW ACCOUNT`
   - `02. DEPOSIT AMOUNT`
   - `03. WITHDRAW AMOUNT`
   - `04. BALANCE ENQUIRY`
   - `05. ALL ACCOUNT HOLDER LIST`
   - `06. CLOSE AN ACCOUNT`
   - `07. MODIFY AN ACCOUNT`
   - `08. EXIT`

3. **Interaction:** Input account details and follow prompts for various operations.

## 📝 **License**

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## 📧 **Contact**

For further information or inquiries, please contact:
- **Name:** Suhail Ahmad
- **Email:** [rbsuhail123@gmail.com](mailto:rbsuhail123@gmail.com)

---

*Thank you for using BankXcellence. We hope it enhances your banking experience!*

