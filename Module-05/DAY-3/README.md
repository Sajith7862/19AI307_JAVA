# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
*/

import java.util.*;
public class SetAndGet {
private int w;
public void getfib() {
        int t1=0,t2=1,sum=0;
        for (int i = 1; i <= w; ++i)
        {
            System.out.print(t1 + " ");
            sum = t1 + t2;
            t1 = t2;
            t2 = sum;
        }
}
public void setfib(int w) {
 this.w = w;
}
public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 int s1=sc.nextInt();
 obj.setfib(s1);
 obj.getfib();
}
}

```



## OUTPUT:

![image](https://github.com/user-attachments/assets/7cd7e453-6b5f-458c-ab80-f32ed21218cf)


## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






