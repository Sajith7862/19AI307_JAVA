# Ex.No:2(A)  STATIC METHOD

## AIM:
To create a java program for calculate cube of a number using static method.

## ALGORITHM :
1.  Start : Begin the process of calculating the cube of a number.
2.	Declare a variable to store input : Declare an integer variable n to hold the number whose cube will be calculated.
3.	Create a Scanner object : Create a Scanner object (sc) to read the input from the user.
4.	Read input from the user : Prompt the user to input an integer value. The input value is stored in the variable n.
5.	Call the cubecal function : Call the function cubecal(n) which computes the cube of the number by performing n * n * n.
6.	Store the result : Store the result of the cubecal function in an integer variable result.
7.	Output the result :
8.	Print the cube of the number using System.out.println("Cube is: " + result);.
9.	End the program.




## PROGRAM:
 ```
/*
Program to implement a Static method using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.Scanner;

public class MultiplyNumbers {
    
    public static double multiply(double num1, double num2) {
        return num1 * num2;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

       
        double num1 = scanner.nextDouble();
        
        double num2 = scanner.nextDouble();

        double product = multiply(num1, num2);
        System.out.println("The product of " + num1 + " and " + num2 + " is: " + product);

        scanner.close();
    }
}

```




## OUTPUT:

![image](https://github.com/user-attachments/assets/63c31194-d5f3-47bd-906b-d56aed9068d8)


## RESULT:
Thus the java program for calculate cube of a number using static method has been executed successfully.

