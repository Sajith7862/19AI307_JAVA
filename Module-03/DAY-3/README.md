# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.Scanner;

public class StringLengthExample {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        String input = scanner.nextLine();

        StringBuilder stringBuilder = new StringBuilder(input);

        int length = stringBuilder.length();

        System.out.println("The size of the String is " + length);

        scanner.close();
    }
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/1f2ee487-3d03-4f89-9c35-2127dcb5b9e9)



## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.



