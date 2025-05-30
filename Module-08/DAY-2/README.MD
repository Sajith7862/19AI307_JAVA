# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To create a java program to append a NUMBER in a file “testout.txt” using Writer.


## ALGORITHM :
1.	It creates a file testout.txt, writes "Welcome to Java File Concept -Reader" to it, and displays this initial content.
2.	It reopens the file in append mode and adds "1234567890" at the end of the existing content.
3.	It reads the file's content (Welcome to Java File Concept -Reader1234567890) and displays it.
4.	The file is deleted using file.delete().
5.	It tries to read the file again, but this throws an exception since the file no longer exists.




## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/


import java.io.*;  
    import java.util.*;
    public class JavaCharArrayReaderReadExample4 {  
       public static void main(String[] args) {  
    Scanner sc=new Scanner(System.in);
    String data=sc.nextLine();
   
    char[] array = new char[40];
    try {
      StringReader input = new StringReader(data);
      input.read(array);
      System.out.println("Data read from the string:");
      System.out.println(array);
      input.close();
    }
    catch(Exception e) {
      e.getStackTrace();
    }
       }  
    }  
```




## OUTPUT:
 


## RESULT:
Thus, the java program to append a NUMBER in a file “testout.txt” using Writer.was executed and verified successfully



