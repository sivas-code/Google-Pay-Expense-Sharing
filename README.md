# Google Pay Expense Sharing

A simple Python-based expense-sharing application built using Jupyter Notebook. It helps friends manage shared expenses, split bills equally or with custom amounts, track transaction history, and calculate balances between users.

## Project Overview

When friends share expenses for lunch, movies, trips, or other activities, calculating who owes money to whom can become confusing. This project simplifies the process by automatically calculating individual shares and suggesting payments to settle outstanding balances.

## Features

- **Manage Friends:** Add and manage multiple users.
- **Add Expenses:** Record expenses with descriptions, payer names, and amounts.
- **Equal Split:** Divide expenses equally among selected friends.
- **Custom Split:** Assign different expense amounts to individual friends.
- **Transaction History:** View recorded expenses and their details.
- **Balance Summary:** Calculate who should receive money and who owes money.
- **Payment Suggestions:** Generate suggested transactions to settle outstanding balances.
- **Interactive Menu:** Use a simple, menu-driven interface in Jupyter Notebook.

## Technology Stack

- **Programming Language:** Python
- **Development Environment:** Jupyter Notebook
- **Libraries:**
  - `PrettyTable` – Displays expenses and balances in table format.
  - `datetime` – Records the date and time of transactions.
- **Data Structures:** Lists and dictionaries

## Requirements

- Python 3.x
- Jupyter Notebook or Anaconda
- PrettyTable library

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/google-pay-expense-sharing.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Open the Project Folder

```bash
cd google-pay-expense-sharing
```

### 3. Install the Required Library

Run this command in your terminal:

```bash
pip install prettytable
```

Alternatively, run the following in a Jupyter Notebook cell:

```python
%pip install prettytable
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells in order. If the entire application is written in one cell, run that cell directly.

## How to Use

1. Run the notebook.
2. Select an option from the application menu.
3. Add friends to the application.
4. Record an expense by entering its description, payer, and total amount.
5. Choose equal splitting or custom splitting.
6. View transaction history to review recorded expenses.
7. Check the balance summary to identify outstanding amounts.
8. Generate payment suggestions to see how friends can settle their balances.
9. Exit the application when finished.

## Example

Suppose three friends share a lunch bill of ₹900.

- Vikram pays ₹900.
- Vikram, Siva, and Naren share the expense equally.
- Each person's share is ₹300.

The application calculates the balances automatically and identifies who should receive money and who needs to pay.

## Project Structure

```text
google-pay-expense-sharing/
│
├── Google_Pay_Expense_Sharing.ipynb
└── README.md
```

## Data Storage

The current version stores friends and expenses in Python lists and dictionaries during execution. The data is temporary and resets when the Jupyter kernel is restarted.

**Note:** This version does not use a database or permanent file storage. Persistent storage can be added in a future version.

## Future Enhancements

- Save transaction data permanently using JSON or a database.
- Add individual transaction history for each friend.
- Improve input validation and error handling.
- Add charts to visualize spending patterns.
- Develop a graphical user interface.
- Add expense reports and monthly summaries.

## Learning Outcomes

This project demonstrates practical use of:

- Python functions and loops.
- Lists and dictionaries.
- Input validation and conditional statements.
- Expense-splitting calculations.
- Data handling and transaction tracking.
- Table formatting using PrettyTable.

## Disclaimer

This is an educational expense-sharing project inspired by common bill-splitting functionality. It is not an official Google Pay application and does not process real payments.

## ScreenShots

<img width="1491" height="433" alt="Screenshot 2026-10-26 125735" src="https://github.com/user-attachments/assets/f13083c0-fa7a-44e0-8372-3d78c5b0c994" />
<img width="1492" height="565" alt="Screenshot 2026-10-26 125608" src="https://github.com/user-attachments/assets/31efcca0-5fbe-4cef-b87f-a08e4086cc56" />
<img width="1487" height="315" alt="Screenshot 2026-10-26 125551" src="https://github.com/user-attachments/assets/714596c5-8c03-46f4-aefb-89f1294b47bc" />


## Author

**Siva Varma G**

---

*Developed as a Python project using Jupyter Notebook.*
