

# Python Bank Account Management System

## Objective

This project is a Python-based bank account management system that allows users to create and manage bank accounts, perform transactions, and retrieve relevant details. The project incorporates key Python concepts such as variables, data structures, functions, file handling, and modules.

## Features

## 1. Account Management

- Users can create new bank accounts.
  - Each account includes:
  - Account holder's name
  - Auto-generated account number
  - Account type (e.g., Savings or Current)
  - Initial balance
- Users can retrieve account details, including name, account number, account type, and current balance.

## 2. Transactions

- Deposit: Add money to an account.
- Withdrawal: Withdraw money while ensuring it does not exceed the balance.
- Transfer: Transfer funds between two accounts.
- Transactions update account balances accordingly.

## 3. File Handling

- Store account details and transaction history using files.
- Use the pickle library to read and write account data.
- Load account data at program start and save updates on termination.
- Append transactions to existing data without overwriting.

## 4. Reports

- View transaction history for a specific account.
- Display details such as date, type (deposit, withdrawal, transfer), and amount.
- Generate summary statistics per account using NumPy functions (e.g., total deposits, total withdrawals, average transaction amounts).

## 5. User Interaction

- Interactive menu options include:
   - Open a new account
   - View account details
   - Perform transactions (deposit, withdrawal, transfer)
   - View transaction history
   - Exit the program
- Conditional statements and loops ensure smooth navigation.

## 6. Error Handling

- Validate inputs (e.g., deposit/withdrawal amounts must be positive).
- Handle errors such as insufficient balance or non-existent accounts.

## 7. Bonus (Optional)

- Implement login functionality for multiple users with username and password protection.
- Use advanced Python features like lambda functions for quick calculations.

## Installation & Setup

1) Clone the repository or download the Project.ipynb file.
2) Ensure you have Python installed (Python 3.6+ recommended).
3)  Install necessary dependencies:

```bash
  pip install numpy
```
4) Run the Jupyter Notebook (Project.ipynb) to execute the program.
## Usage

1) Open the Jupyter Notebook.
2) Run the cells sequentially.
3) Follow the interactive menu to create accounts and perform transactions.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy (for calculations)
- Pickle (for file handling)
