# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: Mohamed Hameem SajithJ
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
![image](https://github.com/user-attachments/assets/0a05b15f-a6e9-4c34-b691-f21bcbfedc7a)



## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
