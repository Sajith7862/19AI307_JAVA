# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
  
*/

import java.util.Scanner;

// Input class to handle user input
class Input {
    private Scanner scanner;

    // Constructor to initialize Scanner object
    public Input() {
        scanner = new Scanner(System.in);
    }

    // Method to read a string value
    public String readString() {
        return scanner.nextLine();
    }

    // Method to read a double value
    public double readDouble() {
        return scanner.nextDouble();
    }
}

// Balance class to handle calculations
class Balance {
    private String name;         // Account holder name
    private String accountNumber; // Account number
    private double initialBalance;
    private double amountDebited;

    // Method to set account details
    public void setDetails(String name, String accountNumber, double initialBalance, double amountDebited) {
        this.name = name;
        this.accountNumber = accountNumber;
        this.initialBalance = initialBalance;
        this.amountDebited = amountDebited;
    }

    // Method to calculate remaining balance
    public double calc() {
        return initialBalance - amountDebited;
    }

    // Method to display account details and balance
    public void display() {
        System.out.println("Name is " + name);
        System.out.println("Account Number is " + accountNumber);
        System.out.println("Balance is " + calc());
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        Input input = new Input();       // Create Input object to read data
        Balance balance = new Balance(); // Create Balance object to manage account details

        String name = input.readString();
        String accountNumber = input.readString();
        double initialBalance = input.readDouble();
        double amountDebited = input.readDouble();

        // Set account details and calculate balance
        balance.setDetails(name, accountNumber, initialBalance, amountDebited);

        // Display account details and remaining balance
        balance.display();
    }
}

```

## OUTPUT:



## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





