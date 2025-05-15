# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.*;
public class Main{
    public static void main (String [] args){
        Scanner sc= new Scanner(System.in);
        int x;
        x=sc.nextInt();
       int y= (int)(Math.pow(x, 3)-2*Math.pow(x-3, 3)+20);
       System.out.println("value: "+y);
        
        
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/8f583b2b-56a5-408b-a9f1-21012c5e5426)


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

