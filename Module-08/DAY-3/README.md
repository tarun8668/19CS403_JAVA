# Ex.No:8(C)             FILTER READER
## AIM:
 To create a java Program to read the content from the file by using Filter Reader 


## ALGORITHM :
1.  Start the Program
2.  Define CustomFilterReader1, extending FilterReader, and override the read() method to replace spaces with $ while reading.
2.	In main(), create a FileOutputStream and a FilterOutputStream to write "India is my country" to a file named javaFile123.txt.
3.	Write the string to the file using filter.write(), then close the FilterOutputStream.
4.	Create a FileReader to read from javaFile123.txt, and wrap it with CustomFilterReader1.
5.	Read and print each character, where spaces are replaced with $, until the end of the file.
6.	Close CustomFilterReader1 and FileReader to free resources


## PROGRAM:
 ```
/*
Program to implement a Filter Reader using Java
Developed by: TARUN S S
RegisterNumber: 212222040171
*/
```

## Sourcecode.java:

```
class CustomFilterReader1 extends FilterReader
{  
    CustomFilterReader1(Reader in)
    {  
        super(in);  
    }  
    public int read() throws IOException
    {
        int x = super.read();  
        if ((char) x == ' ')  
            return ((int) '*');  
        else  
            return x;  
    }  
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/a2aa98fe-b59b-4e88-8431-e1862293a60b)



## RESULT:
Thus the java Program to read the content from the file by using Filter Reader  was executed and verified successfully.









