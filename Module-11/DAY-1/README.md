# Ex.No:11(A)         JAVA TREESET
## AIM:
 To develop a Java program to iterate through all elements in a tree set.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `TreeSet` named `set` to store integers in sorted order
4.	Use a loop to read `n` integers and add each to `set`
5.	Use an enhanced `for` loop to print each element in `set`
6.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

import java.util.*;
public class prog{
    public static void main(String [] args){
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        TreeSet<String> tree_set=new TreeSet<>();
        for(int i=0;i<size;i++){
            tree_set.add(sc.next());
        }
           System.out.println("Original tree set:" + tree_set);  
        Iterator it=tree_set.descendingIterator();
             System.out.println("Elements in Reverse Order:");
while(it.hasNext()){
    System.out.println(it.next());
}
    }
}
*/
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/11da9741-1819-4050-aadd-9262bb066826)


## RESULT:
Thus the java program to iterate through all elements in a tree set was executed successfully.

