# Ex.No:8(C)             FILTER READER
## AIM:
 To create a java Program to read the content from the file by using Filter Reader 


## ALGORITHM :
1.  Start the Program
2.  Define CustomFilterReader1, extending FilterReader, and override the read() method to replace spaces with $ while reading.
2.	In main(), create a FileOutputStream and a FilterOutputStream to write "India is my country" to a file named javaFile123.txt.
3.	Write the string to the file using filter.write(), then close the FilterOutputStream.
4.	Create a FileReader to read from javaFile123.txt, and wrap it with CustomFilterReader1.
5.	Read and print each character, where spaces are replaced with $, until the end of the file.
6.	Close CustomFilterReader1 and FileReader to free resources


## PROGRAM:
 ```
/*
Program to implement a Filter Reader using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
 
*/

        FileInputStream  file1 = new FileInputStream("sample.txt");  
        FilterInputStream filter = new BufferedInputStream(file1);  
        int k =0;  
        while((k=filter.read())!=-1){  
            System.out.print((char)k);  
        }  
          
      
               
 
 
 
```


## OUTPUT:


![image](https://github.com/user-attachments/assets/8c08ed76-9c45-4f74-a628-305fb108f467)

## RESULT:
Thus the java Program to read the content from the file by using Filter Reader  was executed and verified successfully.









