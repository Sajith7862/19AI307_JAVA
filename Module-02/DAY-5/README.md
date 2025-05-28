# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.Scanner;
public class Demo {

    
  public static void main(String[] args)
    {
	  {
		   int i=1,n,sum=0;	
		   Scanner in = new Scanner(System.in);
				    n = in.nextInt();
		  do

		   {
		     sum+=2*i;
		     i++;
		   }while(i<=n);
		   System.out.println ("The Sum of even Natural Number upto " +n+" terms is: " +sum);

		}
    }
}
```



## OUTPUT:
![image](https://github.com/user-attachments/assets/2ec6e53e-fffa-4827-90a9-013cf16a516c)



## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




