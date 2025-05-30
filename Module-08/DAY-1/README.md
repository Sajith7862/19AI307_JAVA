![image](https://github.com/user-attachments/assets/ab2cc611-6cb4-4453-b951-e81ea595b5b2)# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To implement a Java Program to write a String in a file "testout.txt" using FileOutputStream

## ALGORITHM :
1.  Define the string "Welcome to Saveetha" and convert it to a byte array b using getBytes().
2.	Use Scanner to prompt the user for start (starting index) and length (number of bytes) to write from the string.
3.	Open testout.txt using FileOutputStream, and write the specified portion of b from the start index for length bytes, then close the output stream.
4.	Open testout.txt using FileInputStream, read its contents byte-by-byte, convert each byte to a character, and print it to display the file's content.
5.	Use file.delete() to delete testout.txt.
6.	Attempt to read the deleted file, which triggers a FileNotFoundException as the file no longer exists.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/

OutputStream fout=new FileOutputStream("sample.txt",true);
String str="SAVEETHA ENGINEERING COLLEGE";
byte b[]=str.getBytes();
fout.write(b);
fout.close();
                      System.out.println("Successfully Completed");  
           
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/e94fd420-22e1-41ef-823a-64392ba0d314)


## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

