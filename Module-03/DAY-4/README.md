# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.StringTokenizer;

public class TokenizeWithHash {

    public static void main(String[] args) {
        String input = "welcome to java# programming";

        StringTokenizer tokenizer = new StringTokenizer(input, "#");

        while (tokenizer.hasMoreTokens()) {
            System.out.println(tokenizer.nextToken());
        }
    }
}

```



## OUTPUT:
![image](https://github.com/user-attachments/assets/f5aa4c95-110a-4695-8887-e66e58cea458)



## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
