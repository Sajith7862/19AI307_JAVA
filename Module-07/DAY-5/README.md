# Ex.No:7(E)  POLYMORPHISM

## AIM:
To implement method overloading in Java to calculate the sum of two and three numbers demonstrating compile-time polymorphism
## ALGORITHM :
1.	Start the program.
2.	Create a class named SumExample.
3.	Inside the class, define:
     a.	A method sum(int a, int b) to calculate the sum of two numbers.
     b.	An overloaded method sum(int a, int b, int c) to calculate the sum of three numbers.
4.	In the main() method:
      a.	Create an object of the SumExample class.
      b.	Call both versions of the sum() method with appropriate arguments.
      c.	Print the results.
5.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
 
*/

import java.util.*;
class Shape
{

void draw(int a,int b){ }  
}  
class Rectangle extends Shape{  

void draw(int a,int b)
{
     
     int area=(a*b);
     System.out.println("Area of Rectangle:" +area);}  
}  

class Triangle extends Shape{  
void draw(int a,int b)

{
    int area=(a*b)/2;
    System.out.println("Area of Triangle:" +area);}  
}  
public class Main
{
	public static void main(String[] args) 
	{
		  Shape s;  
		  Scanner sc=new Scanner(System.in);
int a=sc.nextInt();
int b=sc.nextInt();
		  
s=new Rectangle();  
s.draw(a,b);  
  
s=new Triangle();  
s.draw(a,b);  
	}
}

```



## OUTPUT:

![image](https://github.com/user-attachments/assets/0021c20f-96dc-40da-b945-86d9e671ec33)


## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism by calculating the sum of two and three numbers using methods with the same name but different parameter lists..


