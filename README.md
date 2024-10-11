**Name**: AKSHAINI SANDRI

**Company**: CODTECH IT SOLUTIONS

**ID**: CT08DS8896

**Domain**: Java Programming

**Duration**: October 5th to November 5th,2024

### Project Overview: Online Banking System

## Project Purpose:
The Online Banking System is designed to simulate core functionalities of a real-world banking environment, providing users with the ability to manage their bank accounts, perform financial transactions, and manage personal information through a Java-based application. It offers essential features such as account creation, deposits, withdrawals, fund transfers, and transaction history.

## Key Functionalities:
**User Registration and Management**:

**User Account Creation**: Users can create an account by providing their name and email.
Personal Information Management: Users can update their name and email as needed.
Bank Account Management:

**Multiple Accounts**: Users can open multiple bank accounts, each identified by a unique account number.
Initial Deposits: Bank accounts are created with an initial deposit amount.
Financial Transactions:

**Deposit**: Users can deposit money into their bank accounts.
Withdrawal: Users can withdraw money, with validation against available funds.
Money Transfer: Users can transfer money between their own accounts or other users' accounts.
Transaction History: The system logs all financial transactions (deposits, withdrawals, transfers) and allows users to view their history.

**System Management and Operations**:
The system provides an interactive, console-based menu for user account management, bank account management, and transaction handling.
Users can log in using their email to access and manage their accounts.
Classes and Structure:

**User Class**:
Manages the personal details of the user.
Maintains a list of the user's bank accounts.

**BankAccount Class**:
Represents individual bank accounts, stores balance information, and records transactions.
Provides methods for depositing, withdrawing, and transferring funds.

**Transaction Class**:
Stores details of individual transactions, such as type, amount, and balance after the transaction.
Used to maintain a history of account activity.

**BankingSystem Class**:
Provides the main interface for user interaction.
Manages the workflow of user registration, account operations, and transaction management.

## Technology Stack:
Programming Language: Java
Data Handling: In-memory storage using ArrayLists to manage users, accounts, and transactions.
User Interface: Console-based, providing text menus for interaction.
Features:
User-Friendly Interface: Simple text-based menus for easy navigation and interaction.
Account Flexibility: Users can manage multiple bank accounts within a single profile.
Transaction Security: Validations ensure that operations like withdrawals and transfers adhere to balance limits.
Transaction History: Full history of account activities, providing transparency for all operations.
Potential for Expansion:
GUI Development: Integrate a graphical user interface for a more intuitive user experience.
Database Integration: Add database support to persist data beyond the runtime of the program.
Additional Banking Features: Expand the system to include functionalities like loan processing, interest calculation, or bill payments.
