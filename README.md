# Bank Management System in Java

A basic banking system built in Java that allows account login, account creation, balance inquiry, fund transfers, transaction history, and account closure.

---

## Features

- **Login** – Existing customers can log in securely.  
- **Create Account** – New customers can register a bank account.  
- **Balance Inquiry** – Check current account balance.  
- **Account Details** – View personal account information.  
- **Fund Transfer** – Transfer money to other accounts.  
- **Transaction History** – Review past transactions.  
- **Account Closure** – Close accounts securely.  

---

## Usage

### 1. Login
- Enter `1` to log in to your existing account.  
- Provide your account number and PIN (found in `credentials.txt`).  
- After login, you will see the menu to access banking features.  

### 2. Create Account
- Enter `2` to create a new account.  
- Follow the prompts and provide required details.

---

## Project Structure

**Classes:**

- `Main` – Entry point; provides options to log in or create an account.  
- `Login` – Handles login and credential validation.  
- `Creation` – Manages new account creation.  
- `BalanceInquiry` – Checks account balance.  
- `AccountDetails` – Displays account information.  
- `Transaction` – Handles fund transfers.  
- `Deletion` – Deletes accounts securely.  

**Data Files:**

- `credentials.txt` – Stores usernames and passwords.  
- `userDB.txt` – Stores account details (number, name, contact).  
- `balanceDB.txt` – Stores account balances.  
- `acc_[accNo].txt` – Stores transaction history for each account.

---



[sawongam](https://github.com/sawongam)
