# Test Cases

This directory contains test cases for the online store application classes.

You can create test classes for each class, such as:

- `ProductTest.java`
- `CartTest.java`
- `CustomerTest.java`
- `StoreTest.java`

An example test class for the `Product` class is provided:

```java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.*;

public class ProductTest {

    @Test
    public void testConstructor() {
        Product product = new Product("Book", "Programming Fundamentals", 29.99, 100);
        assertEquals("Book", product.getName());
        assertEquals("Programming Fundamentals", product.getDescription());
        assertEquals(29.99, product.getPrice(), 0.001);
        assertEquals(100, product.getQuantityInStock());
    }

    @Test
    public void testUpdateQuantity() {
        Product product = new Product("Laptop", "Dell XPS 13", 999.99, 50);
        product.updateQuantity(-10);
        assertEquals(40, product.getQuantityInStock());
    }

    // Add more test cases as needed
}