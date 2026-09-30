# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
```
Program to implement a final & Static using Java
Developed by: KARTHIK A
RegisterNumber:  212225220049
```

## Sourcecode.java:

```java
class Name
{
    String Fname;
    String Mname;
    String Lname;

    void dispName(String fn, String mn, String ln)
    {
        System.out.println("Employee Name: " + fn + " " + mn + " " + ln);
    }

    public static void main(String args[])
    {
        Employee emp = new Employee();

        emp.disp(101);
    }
}

class Employee
{
    int Emp_Id;
    Name obj;

    void disp(int id)
    {
        Emp_Id = id;

        System.out.println("Employee ID: " + Emp_Id);

        obj = new Name();
        obj.dispName("B", "Leo", "John");
    }
}
```





## OUTPUT:
<img width="652" height="205" alt="image" src="https://github.com/user-attachments/assets/c9fb371c-9fc2-421d-a5ed-b88623f8858d" />



## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
