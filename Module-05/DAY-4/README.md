# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```

Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: KARTHIK A
RegisterNumber:  212225220049

```

## Sourcecode.java:
```java
import java.util.Scanner;

class A
{
    int n;
    int fact = 1;

    void factorial(int n)
    {
        this.n = n;

        for (int i = 1; i <= n; i++)
        {
            fact = fact * i;
        }

        System.out.println("Factorial is: " + fact);
    }

    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();

        A obj = new A();

        obj.factorial(n);

        sc.close();
    }
}
```






## OUTPUT:
<img width="583" height="136" alt="image" src="https://github.com/user-attachments/assets/7889fe04-f2a3-424a-a920-5c7bc0f4878e" />



## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
