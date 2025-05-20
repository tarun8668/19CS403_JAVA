# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: Tarun S S
RegisterNumber: 212222040171
*/
```

## Sourcecode.java:
```java
import java.util.Scanner;

public class LargestElement {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int size = scanner.nextInt();
        int[] array = new int[size];

        for (int i = 0; i < size; i++) {
            array[i] = scanner.nextInt();
        }

        int largest = array[0]; // Assume the first element is the largest initially

        for (int i = 1; i < size; i++) {
            if (array[i] > largest) {
                largest = array[i];
            }
        }

        System.out.println("The largest element in the array is: " + largest);

        scanner.close();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e1bdd1a9-71b3-44a4-bba7-de04d93eedf1)


## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




