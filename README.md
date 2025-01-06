#  ✨Banking System✨

## Overview

The Banking System is a console-based Java program that allows users to manage bank accounts. Users can create accounts, deposit or withdraw money, and check account balances interactively. This program demonstrates object-oriented programming concepts in Java.

---

## ⚡Features

1. Create Account:

Users can create new bank accounts by providing an account number and account holder's name.

Ensures unique account numbers.

2. Deposit Money:

Users can deposit money into an account by entering the account number and deposit amount.

Validates deposit amounts to ensure they are positive.

3. Withdraw Money:

Users can withdraw money by providing the account number and withdrawal amount.

Ensures sufficient balance and validates withdrawal amounts.

4. Check Balance:

Displays the current balance for a given account.

5. Exit:

Allows users to exit the program safely.

---

## How to Run

Prerequisites:

- Java Development Kit (JDK) 8 or higher.
- A code editor or terminal to compile and run the program.

Steps:

1. Download the source code file: BankingSystem.java.
2. Compile the program using the command:
3. Run the program using the command:
4. Follow the menu prompts to interact with the program.

---

## Code Structure

Classes:

1. BankAccount:
   - Represents a single bank account.
   - Contains attributes like account number, account holder, and balance.
   - Implements methods for deposit, withdrawal, and displaying balance.

2. Bank:
   - Manages a collection of BankAccount objects.
   - Provides methods to create accounts and find accounts by account number.

3. BankingSystem:
   - The main class that provides a menu-driven interface for user interaction.
   - Handles user input and performs operations like creating accounts, deposits, withdrawals, and balance inquiries.

---

## Sample Usage

Main Menu:

1. Create Account:

2. Deposit Money:

3. Withdraw Money:
  
4. Check Balance:
   
5. Exit:
   
---

## Future Enhancements

- Add persistent storage to save account data across sessions.
- Implement account deletion functionality.
- Include multi-currency support.
- Add transaction history for each account.
- Provide a graphical user interface (GUI) for better user experience.

---

## License

This project is open-source and available for personal or educational use.
