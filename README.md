# Banking Application

## Instructions

In this project, you will implement a simple banking application using Object-Oriented Programming (OOP) concepts. The application should have the following classes:

1. **Account**: Implement a class to represent a bank account. It should have properties such as account number, account holder name, balance, and account type (e.g., savings, checking). Create appropriate methods for depositing, withdrawing, and checking the balance.

2. **Customer**: Implement a class to represent a bank customer. It should have properties such as customer ID, name, address, and a list of accounts associated with the customer.

3. **Bank**: Implement a class to represent the bank itself. It should have a list of customers and methods for adding new customers, retrieving customer information, and performing various banking operations (e.g., opening a new account, transferring funds between accounts).

Additionally, you should implement the following features:

- **Validation**: Ensure that withdrawals cannot result in a negative balance, and that account numbers and customer IDs are unique.
- **Exception Handling**: Handle exceptions appropriately, such as when attempting to withdraw from an account with insufficient funds or trying to access an invalid account or customer.
- **Inheritance and Polymorphism**: Use inheritance and polymorphism concepts to create different types of accounts (e.g., SavingsAccount and CheckingAccount) with specific behaviors or properties.

You can create a `Main` class to create instances of the classes, perform various operations, and test the functionality of your application.

## Getting Started

1. Clone the repository to your local machine.
2. Navigate to the `banking-application` directory.
3. Create a new branch for your work: `git checkout -b your-branch-name`
4. Implement the required classes and their methods according to the instructions above.
5. Write test cases in the `tests` directory to verify the correct implementation of your classes.
6. Commit your changes: `git add .` and `git commit -m "Your commit message"`
7. Push your branch to the remote repository: `git push origin your-branch-name`
8. Create a pull request from your branch to the main branch for review and merging.

## Project Structure
