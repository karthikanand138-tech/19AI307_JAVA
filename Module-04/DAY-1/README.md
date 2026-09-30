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
Program to implement a Constructor using Java
Developed by: KARTHIK A
RegisterNumber:  212225220049

```

## Sourcecode.java:
```java
class circum
{
    int l = 5;
    int w = 6;

    circum()
    {
        int circumference = 2 * (l + w);

        System.out.println("Area of First Rectangle: " + circumference);
        System.out.println("Area of Second Rectangle: " + circumference);
    }

    public static void main(String args[])
    {
        circum sc = new circum();
    }
}
```






## OUTPUT:
<img width="748" height="172" alt="image" src="https://github.com/user-attachments/assets/a5d01e3c-f225-46fb-826f-86a5b7bdff81" />



## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
