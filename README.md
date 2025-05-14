# Bank Management System (Project using MySql and Java)


The Banking Management System is a terminal-based application developed using Java and MySQL, with JDBC used to establish secure communication between the application and the database. The system facilitates basic banking operations such as customer account management, fund transactions, and loan tracking in a structured and efficient manner.

This project simulates the core functions of a real-world banking environment, allowing bank staff or admins to interact with the system through a command-line interface. It emphasizes secure and accurate data handling, with persistent storage using a relational database.

Key Features:
Customer Management: Add, update, and view customer details including contact and address information.
Account Operations: Open new accounts, check account balances, and view account details by customer ID.
Transactions: Perform deposits and withdrawals with automatic balance updates and transaction validation.
Loan Management: Record and view loan details associated with customers, including amount and branch.
Branch Integration: Associate accounts and loans with specific branches using foreign keys.
Search & Reporting: Retrieve and display complete customer profiles including account and loan history.
Data Consistency: Uses SQL constraints and JDBC transactions to ensure reliable data operations.
Case-Insensitive ID Handling: All customer and account IDs are processed without case sensitivity.
Error Handling: Displays appropriate messages for invalid operations like insufficient balance or duplicate IDs.
