# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



## PROGRAM:
 ```
/*
Program to implement a Packages using Java

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090
 
*/

 class Table
  {
    void cube(int n)
     {
      synchronized(this)
      {
          int temp = 1;
         for(int i=1;i<=n;i++)
         { 
             int j=i;
         System.out.println("cube for range value " +n+ " "+i+ ":" + (j*j*j));
         try
         {  
          Thread.sleep(400);  
         }
         catch(Exception e){System.out.println(e);}  
         }  
      }
   }  
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/3255bb25-e5b1-4f79-9e3f-d3c6fdc5b81d)


## RESULT:
Thus the java program for synchronization was executed successfully.

