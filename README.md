# Bank-Account-Management-System

# Bank Management System

A simple console-based application for managing bank accounts, built using Python and MySQL.

## Overview

The Bank Management System streamlines common banking operations—such as account creation, deposits, withdrawals, and balance enquiry—through a user-friendly, menu-driven Python interface. The application interacts with a MySQL database (`bank`) to store and manage customer and balance records securely.

## Key Features

- **Open New Account:**  
  Create a new bank account by entering customer details (Name, Account No., DOB, Phone No., Address, Opening Balance).

- **Deposit Amount:**  
  Add funds to an existing account by specifying the account number and deposit amount.

- **Withdraw Amount:**  
  Withdraw money from an account based on the account number and the required amount, with the system updating the balance accordingly.

- **Balance Enquiry:**  
  Instantly check the current balance of any account using the account number.

- **Display Customer Details:**  
  Retrieve and display stored details for any account holder, including balance.

- **Close an Account:**  
  Delete an account and all its associated data from the system using the account number.

## Technical Details

- **Backend:**  
  Python 3.x using the `mysql-connector-python` library to interface with MySQL.

- **Database:**  
  MySQL database named `bank`, with tables such as `account` (for customer details) and `amount` (for balances).

- **Transaction Handling:**  
  All financial operations (deposit, withdrawal, closing accounts) use SQL transactions for data accuracy and integrity.

- **User Flow:**  
  A menu-driven system repeats after each task, ensuring smooth and continuous operations for the user.

## Requirements

- MySQL server with a database (`bank`) formatted correctly (with required tables/fields).
- Python environment with `mysql-connector-python` installed.
- Configuration of the connection to match your MySQL server’s credentials.

## Usage Notes

- This system is intended for basic demonstration and practice purposes.
- Be sure to set up your MySQL database and tables according to your project’s requirements before running the app.
- Update database credentials in the script as per your environment before use.

