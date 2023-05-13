# EXP-1---JAVA
## AIM :
TO Write a java program to print the Arithmetic operations

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM :

In Java, arithmetic operations are performed using various operators. Here's an overview of the arithmetic operators and their corresponding operations:
1) Addition (+): The addition operator is used to add two values together.
2) Subtraction (-): The subtraction operator is used to subtract one value from another.
3) Multiplication (*): The multiplication operator is used to multiply two values.
4) Division (/): The division operator is used to divide one value by another.
5) Modulo (%): The modulo operator is used to find the remainder of the division between two values.

## PROGRAM :

```java


import java.util.Scanner;
public class Main
{
   public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
       System.out.println("Enter the First NUmber : ");
       int num = sc.nextInt();
       System.out.println("Enter the Second NUmber : ");
       int num1 = sc.nextInt();
       int sum =num+num1;
       int minus = num-num1;
       int multiply = num*num1;
       int div = num/num1;
       int mod = num%num1;
       System.out.println("Addition = "  + sum);
       System.out.println("Difference = "  + minus);
       System.out.println("Multiplication = "  + multiply);
       System.out.println("Division = "  + div);
   }
}

```

## OUTPUT :

<img width="248" alt="image" src="https://github.com/Monisha-11/EXP-1---JAVASCRIPT/assets/93427240/cc0e828d-a32e-4bbd-b715-988e4df51929">

## RESULT :
 Thus the code of arithmetic operation in java is executed successfully and obtain the result.

