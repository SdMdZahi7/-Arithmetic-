# -Arithmetic-
### EXP-1 java program to print the Arithmetic operations
### AIM:
To write a java program to print the Arithmetic operations like Addiction, Subtraction, Division, Remainder of two numbers.

### PROCEDURE:
Import required packages.
Declare main method with the signature "public static void main(String[] args)".
Get two numbers as input.
Perform operations like addition,subtraction,multiplication,division and modulus using the two inputs.
Print the output on display.
### PROGRAM:
~~~
import java.util.Scanner;
public class arithmetic {
    public static void main(String[] args) {
        int add,sub,mul,rem;
        float divide;
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        add=a+b;
        sub=a-b;
        mul=a*b;
        divide=a/b;
        rem=a%b;
        System.out.println("Sum="+add);
        System.out.println("Subtraction="+sub);
        System.out.println("Multiplication="+mul);
        System.out.println("Division="+divide);
        System.out.println("Remainder="+rem);
    }
}
~~~
OUTPUT:
![image](https://github.com/SdMdZahi7/-Arithmetic-/assets/94187572/78667df4-61c3-4588-bfa7-8ea44420235b)

RESULT:
The java program to print the Arithmetic operations like Addiction, Subtraction, Division, Remainder of two numbers was successfully done.
