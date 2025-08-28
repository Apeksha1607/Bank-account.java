

# BankAccount Java Program

A simple Java console application that simulates basic banking operations such as depositing money, withdrawing money, displaying the balance, and viewing account details.

## Features

* Create a bank account with account holder's name, account number, and initial balance.
* Deposit money into the account.
* Withdraw money from the account (with balance check).
* Display current account balance.
* Display full account details.
* Interactive menu-driven interface for user input.

## How to Run

1. Make sure you have Java installed on your machine (JDK 8 or above recommended).
2. Compile the program:

```bash
javac BankAccount.java
```

3. Run the compiled program:

```bash
java BankAccount
```

4. Follow the on-screen prompts to interact with the program.

## Code Structure

* `BankAccount` class:

  * Private attributes: `accountHolderName`, `accountNumber`, `balance`
  * Constructor to initialize account details.
  * Methods for deposit, withdraw, display balance, and display account details.
* `main` method:

  * Uses `Scanner` for user input.
  * Provides a menu-driven interface for banking operations.

## Example Usage

```
Enter account holder name: John Doe
Enter account number: 1234567890
Enter initial balance: ₹1000

--- Bank Menu ---
1. Deposit
2. Withdraw
3. Display Balance
4. Display Account Details
5. Exit
Enter your choice: 1
Enter amount to deposit: ₹500
Amount deposited successfully.

--- Bank Menu ---
1. Deposit
2. Withdraw
3. Display Balance
4. Display Account Details
5. Exit
Enter your choice: 3
Current balance: ₹1500.0
```

## License

This project is open source and free to use.
