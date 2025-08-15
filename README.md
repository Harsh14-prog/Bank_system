Bank Management System in Java

A basic banking system built in Java that allows account login, creation, balance inquiry, fund transfers, transaction history, and account closure.

Features

Login – Existing customers can log in securely.

Create Account – New customers can register a bank account.

Balance Inquiry – Check current account balance.

Account Details – View personal account information.

Fund Transfer – Transfer money to other accounts.

Transaction History – Review past transactions.

Account Closure – Close accounts securely.

Usage

Login

Enter 1 to log in.

Provide account number and PIN (stored in credentials.txt).

Access the menu to use banking features.

Create Account

Enter 2 to create a new account.

Follow prompts and provide required details.

Project Structure

Classes:

Main – Entry point; displays login/create account options.

Login – Handles user login and credential validation.

Creation – Manages new account creation.

BalanceInquiry – Checks account balance.

AccountDetails – Displays account information.

Transaction – Handles fund transfers.

Deletion – Deletes accounts securely.

Data Files:

credentials.txt – Stores usernames and passwords.

userDB.txt – Stores account details (number, name, contact).

balanceDB.txt – Stores account balances.

acc_[accNo].txt – Stores individual account transactions.
