Simple ATM Machine in Java
Overview
This Java program simulates a basic ATM using object-oriented programming (OOP) principles. It allows users to perform various operations, such as checking information, checking the balance, depositing money, and withdrawing money.

Classes
working

- Represents the core functionality of the ATM.
- Contains fields for balance, PIN, name, and age.
- Provides methods for displaying options, inputting PIN, depositing money, checking balance, withdrawing money, and displaying user information.
- The constructor initiates the ATM operations by validating the entered PIN and executing the chosen option.

ATM
- Main class to run the ATM program.
- Creates an instance of the `working` class with initial user details.

Usage
1. Run the `ATM` class to start the ATM program.
2. Enter the PIN when prompted.
3. Choose from options:
   - 1: Check Information
   - 2: Check Balance
   - 3: Deposit Money
   - 4: Withdraw Money

Example
public class ATM {
    public static void main(String[] args) {
        working user1 = new working(3210, 12000, "userName", 21);
    }
}
