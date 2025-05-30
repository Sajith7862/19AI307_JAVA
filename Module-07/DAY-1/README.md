# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `Example1`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `a` and `b` from user input
-	b) Calculate `res = a / b` and print "Result: " followed by `res`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End







## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/

import java.util.Scanner;

public class DivisionByZeroHandling {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        try {
            int num1 = scanner.nextInt();
            int num2 = scanner.nextInt();

            int result = num1 / num2;
            System.out.println("Result: " + result);
        } catch (ArithmeticException e) {
            System.out.println("You Shouldn't divide a number by zero");
        } catch (Exception e) {
            System.out.println("An error occurred: " + e.getMessage());
        } finally {
            scanner.close();
        }
    }
}

```

#


## OUTPUT:

![image](https://github.com/user-attachments/assets/8b909a7f-7af4-45b0-a7f4-ea27e23ac14a)


## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

