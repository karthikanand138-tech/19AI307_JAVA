# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:
 ```
Program to implement a Constructor Chaining using Java
Developed by: KARTHIK A
RegisterNumber:  212225220049
```

## Sourcecode.java:

```java
class College
{
    void display()
    {
        System.out.println("I am a Vehicle");
    }

    public static void main(String args[])
    {
        Student sc = new Student();

        sc.print();
    }
}

class Student extends College
{
    void display()
    {
        System.out.println("I am a Car");
    }

    void print()
    {
        super.display();
        this.display();
    }
}
```





## OUTPUT:
<img width="722" height="212" alt="image" src="https://github.com/user-attachments/assets/7af49410-ed05-4b4c-b928-c073e7492a0c" />



## RESULT:
Thus the java program for constructor chaining was executed successfully.




