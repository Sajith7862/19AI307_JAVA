# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces to read student details and marks, calculate the average, and display the mark sheet.

## ALGORITHM :

1.	Start the program.
2.	Create interface Student:
a.	Declare methods to read name and rollno.
3.	Create interface Studentdet:
a.	Declare a method to read marks of 6 subjects and calculate the average.
b.	Create a class Studentdetails that implements both interfaces:
c.	Define variables for name, roll number, marks array, and average.
4.	Implement all methods from the interfaces.
a.	Create a display() method to show student details and average.
5.	In main() method:
a.	Create an object of Studentdetails.
b.	Call the methods to get input and display results.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
 
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/

class Parent{
    public void display(){
        System.out.println("This is Parent Class");
    }
}
class Child1 extends Parent{
    public void print(){
        System.out.println("This is Child1 Class");
    }
}
class Child2 extends Child1 {
    public void print(){
        System.out.println("This is Child2 Class");
    }
}
class prog{
    public static void main(String [] args){
        Parent obj= new Parent();
        Child1 obj1=new Child1();
        Child2 obj2=new Child2();
        obj.display();
        obj1.print();
        obj.display();
        obj2.print();
        
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/fbe7ce5d-5dcc-4083-9eaa-0d3420102466)


## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces and successfully displays the mark sheet of a student by collecting personal and academic data. 
