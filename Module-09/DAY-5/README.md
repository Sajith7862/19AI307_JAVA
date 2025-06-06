# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/
import java.io.StringWriter;

public class Main {
  public static void main(String[] args) {

    String data = "String Writer";

    try {
      StringWriter output = new StringWriter();

      output.write(data);

      System.out.println("Data in the StringWriter: " + output);

      output.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/150f8777-8c5f-4ff4-baca-88c4d0a0ef89)


## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

