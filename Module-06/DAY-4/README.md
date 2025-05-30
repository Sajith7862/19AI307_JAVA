# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/
class Vehicle {
    public Vehicle() {
        System.out.println("Vehicle class has 3 Child Class");
    }
}

class Car extends Vehicle {
    public Car() {
        super(); 
        System.out.println("Car is the one of the Child of Vehicle Class");
    }
}

class Truck extends Vehicle {
    public Truck() {
        super(); 
        System.out.println("Truck is the one of the Child of Vehicle Class");
    }
}

class Bus extends Vehicle {
    public Bus() {
        super(); 
        System.out.println("Bus is the one of the Child of Vehicle Class");
    }
}

public class Main {
    public static void main(String[] args) {
        Car car = new Car();
        
        Truck truck = new Truck();
        
        Bus bus = new Bus();
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/2c939268-941e-4e3a-a7dd-b2aa427fce05)


## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

