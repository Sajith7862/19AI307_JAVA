# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End








## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/
// Parent Class
class Vehicle {
    // Method to display Vehicle class message
    public void display() {
        System.out.println("Vehicle Class");
    }
}

// Child Class of Vehicle
class Car extends Vehicle {
    // Method to display Car class message
    public void print() {
        System.out.println("Car Class");
    }
}

// Child Class of Car
class Alto extends Car {
    // Method to display Alto class message
    public void show() {
        System.out.println("Alto Class");
    }
}

// Main Class
public class Main {
    public static void main(String[] args) {
        // Create an object of Alto class
        Alto alto = new Alto();

        // Access methods from all the classes
        alto.display(); // Method from Vehicle class
        alto.print();   // Method from Car class
        alto.show();    // Method from Alto class
    }
}

```


## OUTPUT:



## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

