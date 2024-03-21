# Bank Management System

This Python script provides functionalities for managing a bank's database. It allows users to perform various operations such as inserting records, displaying records, searching records, updating records, deleting records, and performing transactions (debit/credit) from the accounts.

## Features

- **Insert Record/Records**: Allows users to insert new records into the bank's database.
- **Display Records**: Users can display records sorted by account number, customer name, or customer balance.
- **Search Record Details**: Users can search for specific records based on the account number.
- **Update Record**: Users can update the details of a customer's record.
- **Delete Record**: Allows users to delete a customer's record from the database.
- **Transactions**: Users can perform debit/withdraw or credit transactions from the accounts.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- MySQL database server

## Setup

1. Install the required Python packages:

2. Ensure your MySQL server is running and accessible.

3. Update the database connection details in the script (`bankmgmt.py`):

- Update the `user`, `passwd`, `host`, `auth_plugin`, and `database` variables in the `mysql.connector.connect()` function call to match your MySQL database configuration.

## Usage

Run the script `bankmgmt.py` using Python:


Follow the on-screen menu instructions to perform various operations.


