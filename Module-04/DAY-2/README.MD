# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End








## PROGRAM:
 ```

Program to implement a Inheritance using Java
Developed by: KARTHIK A
RegisterNumber:  212225220049

```

## Sourcecode.java:
```java
import java.util.Scanner;

class Person
{
    String emp_id;
    String name;
    String dept;

    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        Employee emp = new Employee();

        emp.getDetails(sc);
        emp.display();

        sc.close();
    }
}

class Employee extends Person
{
    void getDetails(Scanner sc)
    {
        name = sc.nextLine();
        emp_id = sc.nextLine();
        dept = sc.nextLine();
    }

    void display()
    {
        System.out.println("Name: " + name);
        System.out.println("Employee ID: " + emp_id);
        System.out.println("Department: " + dept);
    }
}
```






## OUTPUT:
![Image](https://github.com/aswin0603/19AI307_JAVA/blob/main/Module-04/DAY-2/Screenshot%202026-08-25%20210903.png)


## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

