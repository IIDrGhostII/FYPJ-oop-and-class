# Test Cases

This directory contains test cases for the banking application classes.

You can create test classes for each class, such as:

- `AccountTest.java`
- `CustomerTest.java`
- `BankTest.java`

An example test class for the `Account` class is provided:

```java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.*;

public class AccountTest {

    @Test
    public void testDeposit() {
        Account account = new SavingsAccount(1234, "John Doe", 1000.0);
        account.deposit(500.0);
        assertEquals(1500.0, account.getBalance(), 0.001);
    }

    @Test
    public void testWithdraw() {
        Account account = new CheckingAccount(5678, "Jane Smith", 5000.0);
        account.withdraw(1000.0);
        assertEquals(4000.0, account.getBalance(), 0.001);
    }

    // Add more test cases as needed
}