# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Tarun S S
RegisterNumber:  212222040171
*/
```

## Sourcecode.java:

```java
class Student
{
    String name;
    String address;
}
public class Main
{
    public static void main(String[] args)
   {
        Student obj= new Student();        
        obj.name="John";
        obj.address="Chennai";
        System.out.println(obj.name+" "+obj.address);
    }
}
```

## OUTPUT:

<img src ="https://github.com/user-attachments/assets/345e3cd0-6d10-4cf4-be78-8a9e42e21895" width = "50%">


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
