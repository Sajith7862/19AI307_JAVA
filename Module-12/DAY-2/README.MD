# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection.


## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
 
*/

import java.io.*;
import java.lang.*;
import java.util.*;
class Student {
 
    int rollno;
    String name, address;
    public Student(int rollno, String name, String address)
    {
        this.rollno = rollno;
        this.name = name;
        this.address = address;
    }
    public String toString()
    {
         return this.rollno + " " + this.name + " "
            + this.address;
    }
}
class Sortbyname implements Comparator<Student> {
 
    public int compare(Student a, Student b)
    {
 
        return a.name.compareTo(b.name);
    }
}
public class Main {
    public static void main(String[] args)
    {
        ArrayList<Student> ar = new ArrayList<Student>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
        ar.add(new Student(sc.nextInt(),sc.next(),sc.next()));
        }
      
        System.out.println("Unsorted");
 
        
        for (int i = 0; i < ar.size(); i++)
            System.out.println(ar.get(i));
 
         Collections.sort(ar, new Sortbyname());
 
        
        System.out.println("\nSorted by name");
 
        
        for (int i = 0; i < ar.size(); i++)
            System.out.println(ar.get(i));
 
       
    }
}
```




## OUTPUT:



## RESULT:
Thus the java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection was executed successfully




