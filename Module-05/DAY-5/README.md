# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
  
*/

class Calculation {
   int z;
	
   public void addition(int x, int y) {
      z = x + y;
      System.out.println("The sum of the given numbers:"+z);
   }
	
   public void Subtraction(int x, int y) {
      z = x - y;
      System.out.println("The difference between the given numbers:"+z);
   }
}

public class My_Calculation extends Calculation {
   public void multiplication(int x, int y) {
      z = x * y;
      System.out.println("The product of the given numbers:"+z);
   }
	
   public static void main(String args[]) {
      int a = 20, b = 10;
      My_Calculation demo = new My_Calculation();
      demo.addition(a, b);
      demo.Subtraction(a, b);
      demo.multiplication(a, b);
   }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/f8a7cd83-36a3-4fe2-917f-2dbd7f912dd1)


## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

