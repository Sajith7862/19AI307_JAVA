# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.Scanner;

public class SumOfEvenNumbers {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
       
        int size = scanner.nextInt();
        int[] array = new int[size];
       
        for (int i = 0; i < size; i++) {
            array[i] = scanner.nextInt();
        }
        int sum = 0;
        for (int i = 0; i < size; i++) {
            if (array[i] % 2 == 0) { // Check if the element is even
                sum += array[i];
            }
        }
        System.out.println("The Sum of Even Numbers in this Array = " + sum);

        scanner.close();
    }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/12f939fb-f7a9-476f-9409-63078a3b2701)



## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


