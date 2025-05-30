# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Parent have method " display" to display "This is Parent Class". Child1 have method "print" to display "This is Child1 Class" Child1 have method "print" to display "Child2 Class". In Main create object for both child1 and child2 and access its member function.


## ALGORITHM :
1.  Start the Program
2.	Define class `Parent`:
-	a) Method `show()` to print "This is Parent Class"
3.	Define class `Child1` that extends `Parent`:
-	a) Method `print()` to print "This is Child1 Class"
4.	Define class `Child2` that extends `Parent`:
-	a) Method `display()` to print "This is Child2 Class"
5.	In `Main` class `main` method:
-	a) Create `Child1` object `child` and call `show()` and `print()` on it
-	b) Create `Child2` object `chi` and call `show()` and `display()` on it
6.	End




## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java

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

![image](https://github.com/user-attachments/assets/fe2a899b-10ed-476c-9d42-49a0d1d5d5e5)


## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






