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

Program to implement a Data Hiding & Encapsulation using Java
Developed by: KARTHIK A
RegisterNumber:  212225220049

```

## Sourcecode.java:
```java
import java.util.Scanner;

class Employee
{
    private String name1;
    private String name2;

    public void setname(String n1)
    {
        name1 = n1;
    }

    public void setname2(String n2)
    {
        name2 = n2;
    }

    public String get1()
    {
        return name1;
    }

    public String get2()
    {
        return name2;
    }

    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        String name1 = sc.nextLine();
        String name2 = sc.nextLine();

        Employee hl = new Employee();

        hl.setname(name1);
        hl.setname2(name2);

        System.out.println("Employee Name: " + hl.get1());
        System.out.println("Employee Location: " + hl.get2());

        sc.close();
    }
}
```






## OUTPUT:
<img width="775" height="266" alt="image" src="https://github.com/user-attachments/assets/72bbd10a-7b50-47ec-b33e-8e78a69150bf" />



## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
