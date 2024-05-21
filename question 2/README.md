# Question 2: Online Store

## Description

Implement a simple online store application using Object-Oriented Programming (OOP) concepts. The application should have the following classes:

1. **Product**: This class should represent a product in the online store. It should have properties such as product ID, name, description, price, and quantity in stock.

2. **Cart**: This class should represent a shopping cart. It should have properties such as a list of products, total cost, and methods for adding and removing products from the cart.

3. **Customer**: This class should represent a customer of the online store. It should have properties such as customer ID, name, address, and a cart associated with the customer.

4. **Store**: This class should represent the online store itself. It should have a list of products, customers, and methods for managing products, processing orders, and handling customer information.

Additionally, you should implement the following features:

- Validation: Ensure that customers cannot add more products to their cart than the available quantity in stock.
- Exception handling: Handle exceptions appropriately, such as when attempting to add an invalid product to the cart or trying to access an invalid customer or product.
- Inheritance and polymorphism (optional): Consider using inheritance and polymorphism concepts to create different types of products (e.g., PhysicalProduct and DigitalProduct) with specific behaviors or properties.

You can create a `Main` class to create instances of the classes, simulate customer interactions, and test the functionality of your application.

## Instructions

1. Navigate to the `question2` directory.
2. Create a new branch for your work: `git checkout -b your-branch-name`
3. Implement the required classes and their methods according to the question description.
4. Write test cases in the `tests` directory to verify the correct implementation of your classes.
5. Commit your changes: `git add .` and `git commit -m "Your commit message"`
6. Push your branch to the remote repository: `git push origin your-branch-name`
7. Create a pull request from your branch to the main branch for review and merging.