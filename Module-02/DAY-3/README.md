# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 5 values and display the all 5 values from array using single dimensional array.

## ALGORITHM :
1.	Start the program.
2.	2.	Import the `Scanner` class from the `java.util` package
3.	Define a class named `ArrayExample`
4.	Inside the `main` method:
-	a) Create a `Scanner` object called `scanner` to take user input
-	b) Declare an integer array `values` of size 5
-	c) Use a `for` loop to iterate from `i = 0` to `i < 5`:
-   d) Take input from the user and store it in `values[i]`
5.	Print "Elements in Array are :"
6.	Use another `for` loop to iterate from `i = 0` to `i < 5`:
-	a) Print each element in `values` followed by a space
7.	Close the `scanner` to release resources
8.	End





## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

public class StringArrayExample {

    public static void main(String[] args) {
        String[] stringArray = {"one", "two", "three", "four"};

        System.out.println("These are elements of one Dimensional array:");
        for (String element : stringArray) {
            System.out.println(element);
        }
    }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/a0338cbe-755b-4467-9dee-4e76f3471675)


## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.


