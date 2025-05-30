# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
 Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/

FileWriter writer = new FileWriter("sample.txt");  
    BufferedWriter buffer = new BufferedWriter(writer);  
    Scanner sc=new Scanner(System.in);
    String str=sc.nextLine();
int index=sc.nextInt();
    int length=sc.nextInt();
    buffer.write(str,index,length);
    
    buffer.close();  
    
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/842a54f3-97cc-4244-a9c5-b33c2514efc4)



## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


