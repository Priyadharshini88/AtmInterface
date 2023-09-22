# AtmInterface
# CODSOFT-JAVA-DEVELOPMENT-TASK 3
Repository showcasing my completed projects and tasks during my Java Development internship at CODSOFT. Here, you'll find the code and documentation for the various assignments and projects I worked on, demonstrating my growth and skills as a Java intern at CODSOFT.

# Task 3
# ATM INTERFACE
Create a class to represent the ATM machine.
Design the user interface for the ATM, including options such as withdrawing, depositing, andchecking the balance.
Implement methods for each option, such as withdraw(amount), deposit(amount), andcheckBalance().
Create a class to represent the user's bank account, which stores the account balance.
Connect the ATM class with the user's bank account class to access and modify the account balance.
Validate user input to ensure it is within acceptable limits (e.g., sufficient balance for withdrawals).
Display appropriate messages to the user based on their chosen options and the success or failure of their transactions.
# Approach Overview
The ATM Machine program is designed to simulate a simple ATM interface for a bank account. It consists of two main classes: BankAccount and ATM, along with a Main class to start the program. The approach for building the ATM machine can be broken down into the following steps:

BankAccount Class:

Represents a bank account and maintains the account balance.
Provides methods to deposit and withdraw funds from the account.
Validates input for deposit and withdrawal to ensure the amount is within acceptable limits.
ATM Class:

Represents the ATM machine and connects to a specific BankAccount instance.
Displays a menu with options for checking balance, depositing, and withdrawing funds.
Accepts user input and processes the selected option accordingly.
Uses exception handling to handle invalid user input and provide appropriate messages.
Main Class:

Initializes a BankAccount instance with an initial balance.
Creates an ATM instance connected to the bank account.
Starts the ATM interface, allowing users to interact with their bank account.
Display and User Interaction:

The ATM interface displays a menu with options to check balance, deposit, and withdraw.
User input is taken using the Scanner class and processed based on the selected option.
Appropriate messages are displayed for each transaction, including successful and failed attempts.
Input Validation:

Input validation is performed to ensure that deposit and withdrawal amounts are valid and within the account balance.
Exiting the Program:

Users can exit the program by choosing the "Exit" option from the menu.
This program demonstrates basic object-oriented programming principles, including class design, encapsulation, and method interactions. It also showcases exception handling for handling user input errors and providing user-friendly feedback.

Feel free to explore the code and make modifications to adapt it to your needs or to add more advanced features.

# Getting Started
Follow these steps to get your Java project up and running on your local machine.

# Prerequisites
Before you begin, ensure you have the following installed:

Java Development Kit (JDK) Download
Git (for cloning the repository) Download
# After installation
-Clone or download this repository to your local machine. -Open the NumberGussingGame.java file in any Java IDE to run the code.

# Usage
Follow these steps to play the Number Guessing Game in Java.

# Clone the repository:
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
# After Cloning the source code
Compile the java program  javac Main.java
Run the program java Main
ATM Menu: The program will display the ATM menu with the following options: -Check Balance -Deposit -Withdraw -Exit
Choose an Option: -Choose a menu option by entering the corresponding number (1, 2, 3, or 4) and pressing Enter.
Check balance: -Select option 1 to check the account balance. -The program will display the current balance of the bank account.
Deposit Funds -Select option 2 to deposit funds. -Enter the amount you wish to deposit when prompted. -The program will display the new balance after the deposit.
Withdrawl funds: -Select option 3 to withdraw funds. -Enter the amount you wish to withdraw when prompted. -The program will display the new balance after the withdrawal.
Exit the program: -Select option 4 to exit the program. -The program will display a thank you message and close.
Invalid Input Handling: -If you enter invalid input (non-numeric values for amounts), the program will prompt you to enter a valid amount. -If you attempt to withdraw more funds than your balance allows, the program will notify you of the insufficient balance.
Feel free to modify the code and customize the ranges, maximum attempts, and other settings to tailor the game to your preferences.

Note: Make sure you have the Java Development Kit (JDK) installed on your system before running the program.
