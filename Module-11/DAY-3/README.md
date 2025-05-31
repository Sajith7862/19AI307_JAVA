# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To Create a java program to display the contains key of 104 and to retrieve the key and value using linked hash map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `LinkedHashMap` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	Check if the `hash` contains the key `104` and print the result
7.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
  
*/

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  LinkedHashMap<Integer,String> map=new LinkedHashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
  boolean isEmpty = map.isEmpty(); System.out.println("Is HashMap is empty: " + isEmpty);
 }  
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/e19e57d5-3e0c-40eb-afa3-ea0b4f629303)


## RESULT:
Thus the  java program to display the contains key of 104 and to retrieve the key and value using linked hash map was executed successfully.








