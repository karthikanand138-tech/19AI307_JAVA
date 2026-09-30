# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```

Program to implement a HAS-A RelationShip
Developed by: KARTHIK A
RegisterNumber:  212225220049

```

## Sourcecode.java:
```java
import java.util.Scanner;

class ArrayData
{
    int arr[];
    int size;

    void readArray()
    {
        Scanner sc = new Scanner(System.in);

        size = sc.nextInt();

        arr = new int[size];

        for (int i = 0; i < size; i++)
        {
            arr[i] = sc.nextInt();
        }
    }

    public static void main(String args[])
    {
        ArrayData data = new ArrayData();

        data.readArray();

        ArrayOperation operation = new ArrayOperation();

        operation.findMax(data);
    }
}

class ArrayOperation
{
    void findMax(ArrayData data)
    {
        int max = data.arr[0];

        for (int i = 1; i < data.size; i++)
        {
            if (data.arr[i] > max)
            {
                max = data.arr[i];
            }
        }

        System.out.println("Largest number is: " + max);
    }
}
```






## OUTPUT:
<img width="766" height="265" alt="image" src="https://github.com/user-attachments/assets/460d5302-fbbe-4cd6-9b78-09b457aaf789" />



## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

