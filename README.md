# OnlineQuizPlatform

This project simulates a basic banking system where users can perform essential banking operations such as checking their balance, depositing money, withdrawing funds, and exiting the application. It is an excellent project for beginners to learn and practice fundamental programming concepts.

Key Features:
Check Balance: The user can check their current account balance, which starts at zero.
Deposit Money: The user can deposit an amount into the account, and the program updates the balance accordingly.
Withdraw Money: The user can withdraw money from the account, but only if they have sufficient funds.
Exit Program: The user can exit the program at any time.
Main Concepts Covered:
Scanner Class:

The program uses the Scanner class to take input from the user. This allows the user to interact with the application by entering their choice and amounts to deposit or withdraw.
Methods:

The application is organized into separate methods to handle different tasks like checkBalance(), deposit(), and withdraw(). This structure makes the code modular, easier to read, and reusable.
Conditionals (if-else):

When depositing or withdrawing money, the program checks if the amounts are valid (greater than zero) and whether there are sufficient funds for a withdrawal. This ensures proper banking operations.
Loops:

A while loop is used to continuously show the menu and allow the user to perform multiple actions until they choose to exit. This provides an interactive experience.
Switch-Case:

The program uses a switch statement to handle the user’s choice from the menu. This structure allows for efficient selection of options and makes the code more readable.
Flow of the Program:
The user is repeatedly shown a menu with options (check balance, deposit, withdraw, exit).
Based on the user’s input:
If they choose to deposit, the balance is updated.
If they choose to withdraw, the balance is decreased, provided there are sufficient funds.
If they check the balance, the current amount is displayed.
The program will keep running until the user chooses to exit.
Benefits of the Project:
Beginner-Friendly: The project introduces basic Java concepts like input handling, loops, methods, and conditional statements in a practical, real-world scenario.
Interactive: It creates an engaging interface for users to perform banking tasks, reinforcing the connection between user input and program functionality.
Modular Design: The use of methods makes the program organized and easy to extend. You can easily add new features (like multiple accounts or transaction history) in the future.
This project provides a hands-on experience in designing a simple, yet functional application that mirrors basic banking operations and helps reinforce core programming skills.
