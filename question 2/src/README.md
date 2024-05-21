# Source Code

This directory contains the source code files for the online store application.

You can start by creating the following classes:

- `Product.java`
- `Cart.java`
- `Customer.java`
- `Store.java`

Additionally, you can create a `Main` class to instantiate objects, simulate customer interactions, and test the functionality of your application.

An example `Main` class is provided to help you get started:

```java
public class Main {
    public static void main(String[] args) {
        // Create a new store
        Store store = new Store();

        // Add some products to the store
        Product product1 = new Product("Book", "Programming Fundamentals", 29.99, 100);
        Product product2 = new Product("Laptop", "Dell XPS 13", 999.99, 50);
        store.addProduct(product1);
        store.addProduct(product2);

        // Create a customer
        Customer customer = new Customer("John Doe", "123 Main St.");

        // Add products to the customer's cart
        customer.getCart().addProduct(product1, 2);
        customer.getCart().addProduct(product2, 1);

        // Process the order
        store.processOrder(customer);

        // Print the customer's order details
        System.out.println("Customer: " + customer.getName());
        System.out.println("Order Total: $" + customer.getCart().getTotalCost());
    }
}