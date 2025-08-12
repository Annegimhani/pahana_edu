# Pahana Edu Online Billing System

## Overview
This project is a web-based Online Billing System developed for Pahana Edu, a leading bookshop in Colombo City. It automates customer account management, item management, and billing processes, replacing manual methods with an efficient, computerized solution. Built using Java EE with a MySQL database, it fulfills the requirements of the CIS6003 Advanced Programming module at ICBT Campus.

This GitHub repository contains the source code, UML diagrams, and documentation for the system.

## Features
- **User Authentication**: Secure login with username and password validation.
- **Customer Management**: Add, edit, and display customer details (account number, name, address, telephone number).
- **Item Management**: Add, update, and delete item information (e.g., book titles, prices, stock).
- **Billing Calculation**: Compute and print bills based on units consumed or items purchased.
- **Help Section**: Provides user-friendly system usage guidelines for new users.
- **Exit System**: Secure logout functionality.
- **Additional Features**: Session management for secure user interactions.

The system uses a three-tier architecture (Presentation, Business Logic, Data Access) and incorporates design patterns like Singleton and Factory for maintainability and scalability.

## Technologies Used
- **Programming Language**: Java EE (Servlets, JSP)
- **Frontend**: HTML, CSS
- **Database**: MySQL (managed via MySQL Workbench)
- **IDE**: Eclipse IDE
- **Build Tool**: Maven
- **Version Control**: Git (with GitHub for repository management)
- **Web Server**: Apache Tomcat


## Usage
1. **Login**: Use default credentials (e.g., admin/admin) or register a new user.
2. **Add Customer**: Navigate to customer management, enter details like account number, name, address, and phone number.
3. **Manage Items**: Add, update, or delete items (e.g., books with price and stock details).
4. **Generate Bill**: Select a customer, input items or units consumed, and generate/print the bill.
5. **View Account Details**: Retrieve and display customer information from the database.
6. **Help Section**: Access guidelines via the help menu.
7. **Logout**: Securely exit the system.

## Version Control and Workflows
The project uses Git for version control, hosted on GitHub. Key practices:
- **Branching**: Feature branches  merged into `main` via pull requests.
- **Commits**: Frequent commits with clear messages (e.g., `feat: implement user authentication servlet`).
- **Updates**: Daily commits during development to reflect feature additions 

Repository Link:https://github.com/Annegimhani/Pahana-Edu-Billing-System.git
GitHub - Annegimhani/Pahana-Edu-Billing-System


