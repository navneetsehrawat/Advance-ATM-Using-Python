This simple Python program simulates a basic ATM machine where users can log in using a PIN and perform standard banking operations such as checking balance, depositing money, and withdrawing money.

📌 Features

PIN authentication (Default PIN: 1234)

Check current account balance

Deposit money

Withdraw money with balance validation

Simple, beginner-friendly menu system

Uses basic Python concepts like input handling and conditional statements

🧾 How the Program Works

The program starts with an initial balance of ₹5000.

The user is asked to enter a 4-digit PIN.

If the PIN is correct, the menu appears with four options:

1 → Check Balance

2 → Deposit Money

3 → Withdraw Money

4 → Exit

Based on the user’s choice, the program performs the selected operation using if-elif-else conditions.

For withdrawals, the program checks whether sufficient balance exists.

If the PIN or choice is incorrect, an error message is displayed.

▶️ How to Run the Program

Save the code in a file named atm.py

Run it using:

python atm.py


Enter PIN: 1234

📂 Code Overview

The program uses:

Variables (for balance)

Input() for user interaction

Conditional statements to handle menu logic

Basic arithmetic operations to update balance

📌 Note

This is a beginner-level ATM simulation.
It does not store data permanently—balance resets every time the program runs.
