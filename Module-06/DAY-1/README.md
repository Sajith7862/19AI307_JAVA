# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End






## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java

Developed by: Mohamed Hameem Sajith J
RegisterNumber:  212223240090

*/
class Login {
    private String userName;  
    private String password;  

    public Login(String userName, String password) {
        this.userName = userName;
        this.password = password;
    }

    class ValidateCredentials {
        public void validate() {
            System.out.println(userName+" "+ password);
        }
    }
}

public class Main {
    public static void main(String[] args) {
        Login login = new Login("Saveetha", "12345");

        Login.ValidateCredentials validator = login.new ValidateCredentials();

        validator.validate();
    }
}


```

## OUTPUT:

![image](https://github.com/user-attachments/assets/9b8e3416-9a4b-4cf9-8af7-f523b249c9f0)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

