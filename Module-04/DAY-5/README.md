# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

	1.	Start the program.
2.	Define a class Employee:
    a.	  Declare two private string variables: name and designation.
3.	Create a parameterized constructor in Employee:
4.	Accept two parameters: name and designation.
5.	Assign the parameters to the class fields.
6.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
7.	Create another class Sample with the main method.
8.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
9.	Print the values of empName and empDesg.
10.	End the program


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java

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

![image](https://github.com/user-attachments/assets/28205a91-cb40-4e23-996b-1d9d7588b4a8)


## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


