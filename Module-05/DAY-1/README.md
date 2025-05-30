# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End





## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.*;
class Account {  

private long acc_no;  


public long getAcc_no() {  
    return acc_no;  
}  
public void setAcc_no(long acc_no) {  
    this.acc_no = acc_no;  
}  

    
}  
public class TestEncapsulation {  
public static void main(String[] args) {  
    Scanner sc=new Scanner(System.in);
    Account acc=new Account();  
   
    acc.setAcc_no(sc.nextLong());  
    
  
    System.out.println(acc.getAcc_no());  
}  
}  
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/b2a42935-2700-4ae4-9f1c-91ace724e6ca)



## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
