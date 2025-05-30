# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :
1.	The user enters a string (data), followed by two integers (start and length) specifying the starting position and number of characters to write.
2.	The string data is converted to a byte array (array).
3.	Using ByteArrayOutputStream, it writes length bytes from array, starting at start.
4.	The written data is retrieved as a string (streamData) and displayed, showing the original input and the specific segment written to the stream.
5.	Any exceptions are caught and handled, displaying stack trace information if an error occurs.




## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/

import java.io.ByteArrayInputStream;
import java.util.*;
public class Main {
  public static void main(String[] args) 
  {
      byte[] array = {1, 2, 3, 4};
      try
      {
          
      ByteArrayInputStream input =new ByteArrayInputStream(array);
      input.skip(1);
      System.out.print("Input stream after skipping 1 bytes: ");
      
      int data=input.read();
      while(data!=-1){
          System.out.print(data+", ");
          data=input.read();
      }
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
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





