# project3
This is a bank management system CLI project.



This project is a bank management system that performs core banking operations. It enables users to manage customers, transactions, and accounts in a simple and efficient manner. The system is built using Python and SQLAlchemy to handle the database interactions and management



Key Entities:
Customer: Contains basic information such as customer ID, first name, and last name.
Account: Represents an account with attributes like account type (savings or current) and balance.
Transaction: Logs customer transactions, including date, description, amount, and links to the account and customer.




Features
This bank management system allows users to:
View existing database records.
Create new records for customers, transactions, and accounts.
Delete customer records and associated data from the database.



Technologies Used
Python: Core language for logic and functionality.
SQLAlchemy: ORM (Object-Relational Mapping) for database interaction.
pytest: Used for testing the functionality of the system.



Installation
To get the project running locally, follow these steps:

Clone the repository:
git clone https://github.com/34Mbithi/project3


Install the required dependencies:

pipenv install
Activate the virtual environment:
pipenv shell




Main Menu Options:

 S: View records (Customer, Transaction, Account)

 F: Add new records (Customer, Transaction, Account)

 R: Remove a customer and their associated data
 
 Q: Quit the program





View Records Menu:
Customer Records: Press C to list all customers.


Transaction Records: Press T to view transaction records for a specific customer.


Account Records: Press A to view account records for a customer.
Back to Main Menu: Press B to return.





Add Records Menu:
Add Customer: Press C to add a new customer. Enter first and last names.


Add Transaction: Press T to add a new transaction (requires account ID, amount, description).


Add Account: Press A to create a new account (specify account type, initial deposit, and customer ID).



Back to Main Menu: Press B to return.



Delete Customer:
To remove a customer and their related data:

Press R in the main menu, enter the customer ID, and confirm the deletion.
