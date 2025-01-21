

# Banking Management System

A simple banking management system built in Java using Java Swing for the graphical user interface (GUI) and MySQL for database management. This system allows users to perform basic banking operations like deposits, withdrawals, balance inquiries, pin changes, and mini statements.

## Features

- **User Authentication**: Secure login using a PIN.
- **Deposit and Withdrawal**: Ability to deposit and withdraw money from the account.
- **Balance Enquiry**: Check the current balance of the account.
- **Mini Statement**: View a mini statement with transaction history.
- **Pin Change**: Change the account PIN securely.
- **Fast Cash**: Withdraw pre-set amounts like Rs 100, 500, 1000, 2000, etc.
- **Transaction History**: Displays a detailed list of all transactions (Deposit/Withdrawal).

## Prerequisites

- **Java**: Version 8 or higher.
- **MySQL**: Database server for storing user data.
- **JDBC**: Java Database Connectivity for database integration.
- **Java Swing**: For building the graphical user interface.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/banking-management-system.git

2. **Set up MySQL Database:**

Create a database named bankmanagementsystem.
Create the required tables (e.g., login, bank, etc.).
Use the provided SQL scripts to set up the necessary structure for the database.

3. **Configure the Database Connection:**

Open Conn.java.
Update the database connection URL, username, and password according to your local MySQL setup.




4. **Run the Application:**

Compile and run the Java classes.
Start by running the main class (typically Login.java or the first screen you encounter).


**How It Works**
Login Screen: The user enters their PIN to authenticate.
Main Menu: After login, users can access options like deposit, withdrawal, balance enquiry, mini statement, pin change, and fast cash.
Database: All user transactions are logged in a MySQL database, and user data (such as PIN) is stored securely.






