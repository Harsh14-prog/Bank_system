Bank Management System in Java

A basic banking system implemented in Java, providing account login, account creation, balance inquiry, fund transfers, and more.

Features

Login: Existing customers can log in to their accounts.

Create Account: New customers can create a bank account.

Balance Inquiry: Customers can check their account balance.

Account Details: View personal account information.

Fund Transfer: Transfer money to other accounts.

Transaction History: Check past transactions.

Account Closure: Close a bank account securely.

Usage

Login: Enter 1 to log in to an existing account.

Enter your account number and PIN (stored in credentials.txt).

Access the menu to use banking features.

Create Account: Enter 2 to create a new account.

Follow the instructions and provide the required details.

Project Structure

The program is organized into the following main classes:

Main: Entry point of the application, provides options to log in or create a new account.

Login: Handles user login and credential verification.

Creation: Facilitates new account creation.

BalanceInquiry: Checks the balance of a user's account.

AccountDetails: Displays account information.

Transaction: Handles fund transfers between accounts.

Deletion: Allows account closure and deletes user data.

Data Files

credentials.txt: Stores usernames and passwords of registered users.

userDB.txt: Stores account details such as account number, name, and contact information.

balanceDB.txt: Maintains account balances for all users.

acc_[accNo].txt: Stores transaction history for each account.
