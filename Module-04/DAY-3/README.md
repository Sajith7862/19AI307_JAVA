# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:

 ```
/*
Program to implement a Inheritance using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.*;
interface Employee
{
    void get();
}
interface Employeesalary
{
   void gets();
}
class Employeedetails  implements Employee, Employeesalary
{
    Scanner sc= new Scanner(System.in);
    public String name;
    public int Id;
    public String Sal;
    public String des;
    public void get()
    {
        Id= sc.nextInt();
      
        name =sc.next();
        
    }
    public void gets()
    {
        Sal= sc.next();
        des =sc.next();
        
    }
    public void display()
    {
        System.out.println("Roll No : "+Id);
        System.out.println("Name : "+name);
         System.out.println("Year : "+Sal);
        System.out.println("Department  : "+des);
       
    }
    
   
    
}
public class Main
{
	public static void main(String[] args) 
	{
	Employeedetails E= new Employeedetails();
	E.get();
	E.gets();
	E.display();
	}
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/478b5767-3c7a-4b9f-98c0-8a668bda82dc)



## RESULT:
Thus the java program for constructor chaining was executed successfully.




