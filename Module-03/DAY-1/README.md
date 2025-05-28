# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.Scanner;

public class SplitSentence {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);


        String sentence = scanner.nextLine();

        String[] words = sentence.split(" ");

        for (String word : words) {
            System.out.println(word);
        }

        scanner.close();
    }
}


```


## OUTPUT:

![image](https://github.com/user-attachments/assets/487f650f-560a-49ed-b00b-0d370c53323c)


## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

