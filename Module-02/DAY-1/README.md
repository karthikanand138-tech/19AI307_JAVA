# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Car with attributes brand, model, year. Create 2 objects and print their details.

## AIM:
To create a class Car with attributes brand, model, year. Create 2 objects and print their details.

## ALGORITHM :
1. Start.

2. Create a Car class with brand, model, and year.

3. Create the first car object and assign its details.

4. Create the second car object and assign its details.

5. Print the details of the first car.

6. Print the details of the second car and stop.




## PROGRAM:
 ```
Program to implement a Class and Objects using Java
Developed by: KARTHIK
RegisterNumber:  212225220049
```

## SOURCE CODE:

```
class Car {
    String brand;
    String model;
    int year;
}

public class prog {
    public static void main(String[] args) {
        Car car1 = new Car();
        car1.brand = "Toyota";
        car1.model = "Innova";
        car1.year = 2022;

        Car car2 = new Car();
        car2.brand = "Hyundai";
        car2.model = "i20";
        car2.year = 2021;

        System.out.println("Car 1: " + car1.brand + " " + car1.model + " " + car1.year);
        System.out.println("Car 2: " + car2.brand + " " + car2.model + " " + car2.year);
    }
}
```






## OUTPUT:

<img width="669" height="262" alt="image" src="https://github.com/user-attachments/assets/7dcbd736-436c-45ac-86f9-934d9be134ce" />


## RESULT:
The program is successfully impletmented and output is verified. 


