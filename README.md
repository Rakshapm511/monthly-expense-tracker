# 💰 Monthly Expense Tracker

A Python and MySQL based personal expense tracking application that helps users record, manage, search, and analyze their expenses.

## 📌 Features

- ➕ Add expenses
- 👀 View all expenses
- 🔍 Search expenses by category or ID
- ✏️ Edit expense details
- 🗑️ Delete expenses
- 📊 Generate monthly expense summaries
- 📂 View spending by category
- 💰 Find the highest expense
- 🎯 Set a monthly budget
- 🔄 Update an existing budget
- ⚠️ Get a warning when the monthly budget is exceeded

## 🛠️ Technologies Used

- Python
- MySQL
- MySQL Connector/Python

## 📁 Expense Categories

The application supports:

- Food
- Travel
- Shopping
- Bills
- Other

## 🗄️ Database

The project uses a MySQL database named:

expense_tracker

The application stores expense information such as:

- Expense ID
- Expense date
- Category
- Amount
- Description

## ⚙️ How to Run

### 1. Install Python

Make sure Python is installed on your computer.

### 2. Install MySQL

Install MySQL Server and create the required database and tables.

### 3. Install the required Python package

Open Command Prompt or PowerShell in the project folder and run:

pip install mysql-connector-python

### 4. Configure the database

Update the MySQL connection details in the Python program according to your local MySQL setup.

## 🔐 Database Password Setup

This project uses MySQL for the database.

Before running the project, update the database configuration with **your own MySQL username and password**.

### 1. Open the database configuration file

Open:

```text
config.py
```

You will find something similar to:

```python
DB_CONFIG = {
    "host": "localhost",
    "user": "root",
    "password": "YOUR_MYSQL_PASSWORD",
    "database": "expense_tracker"
}
```

### 2. Enter your MySQL password

Replace:

```text
YOUR_MYSQL_PASSWORD
```

with the password you created for your **own MySQL installation**.

For example:

"password": "mypassword123"


⚠️ **Do not use my password. Use the password configured on your computer.**

### 3. Create the database

Open MySQL and run:

CREATE DATABASE expense_tracker;

Then make sure the required tables are created according to the SQL file provided in this project.

### 4. Install the required packages

Open the project folder in PowerShell or Command Prompt and run:

pip install -r requirements.txt

### 5. Run the project

Start the Flask application:

python app.py

Then open the URL shown in the terminal, usually:

http://127.0.0.1:5000

### ⚠️ Important

Do not upload your personal MySQL password to GitHub.

If you are sharing this project publicly, replace your actual password with a placeholder such as:

YOUR_MYSQL_PASSWORD


Each person who downloads the project should enter their own MySQL password.

### 5. Run the application

python ExpenseTracker.py

## 📋 Main Menu

The application provides options to:

1. Add Expense
2. View Expenses
3. Search Expense
4. Edit Expense
5. Monthly Summary
6. Set Budget
7. Delete Expense Data
8. Exit

## 🎯 Project Purpose

This project was developed to practice Python programming, MySQL database connectivity, CRUD operations, searching, monthly expense analysis, and budget management.

## 👩‍💻 Author

Raksha P.M