Overview
This Java application is a comprehensive employee banking system that demonstrates object-oriented programming concepts with a GUI interface. The system models a company with employees who have bank accounts, allowing for account management, employee sorting by balance, and data entry through graphical interfaces.

Features
Bank Account Management: Create and manage bank accounts with credit/debit functionality

Employee System: Track employee details including name, age, and associated bank account

Company Management: Organize employees within a company structure

GUI Interfaces: Multiple graphical interfaces for data entry and system interaction

Data Validation: Input validation for all user entries

Sorting Functionality: Sort employees by their bank account balance

Class Structure
Core Classes
BankAccount

Manages bank name and balance

Provides credit/debit operations

Includes input validation for transactions

Employee

Stores employee details (name, age)

Associates each employee with a BankAccount

Provides getters/setters for all properties

Company

Contains company details (name, address)

Manages an array of Employees

Implements sorting of employees by bank balance

GUI Classes
BankAccountGui

Interface for entering bank account details

Validates inputs before proceeding

EmployeeGui

Interface for entering employee details

Links to BankAccountGui for account information

CompanyGui

Main interface for entering company details

Initiates the employee entry process

How to Run
Option 1: Run through Main class

Execute the Main class in the tester package

This will demonstrate both GUI and console functionality

Option 2: Run individual GUIs

Run CompanyGui to start with company details

Run EmployeeGui to start with employee details

Run BankAccountGui to start with bank account details

Usage Flow
Start with CompanyGui to enter company details

Specify number of employees

For each employee:

Enter name and age in EmployeeGui

Enter bank details in BankAccountGui

The system will automatically:

Validate all inputs

Create the objects

Sort employees by balance

Console Demonstration
The Main class includes a console demonstration that:

Creates sample bank accounts

Creates sample employees

Creates a sample company

Assigns random balances

Sorts employees by balance

Prints all information to console

Input Validation
All GUI forms include validation for:

Empty fields

Numeric values where required

Negative amounts for debit operations

Sufficient balance for withdrawals

Sorting Algorithm
The system implements a bubble sort algorithm to sort employees by their bank account balance in ascending order.

Dependencies
Java Swing for GUI components

Java AWT for layout management

No external libraries required

Future Enhancements
Add database persistence

Implement more sophisticated sorting algorithms

Add additional bank account types

Include transaction history

Add graphical representations of data
