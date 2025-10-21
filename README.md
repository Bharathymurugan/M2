# EX-06 - Looping
## AIM:
Write a C Program to print the string "WINDOWS" n number of times.
## ALGORITHM:
1.	Declare two integer variables to store the values of M and N.
2.	Use the printf function to prompt the user to enter the values of M and N.
3.	Use the scanf function to read the values of M and N from the user.
4.	Use a loop (for or while) to iterate from M to N.
5.	Inside the loop, check if the current number is even.
6.	If the current number is even, print it.
7.	Continue the loop until you have iterated through all numbers from M to N.

## PROGRAM:
#include<stdio.h>
int main()
{
    int n,i;
    scanf("%d", &n);
    for(i=1;i<=n;i++){
        printf("WINDOWS\n");
    }
    return 0;
}

## OUTPUT:
<img width="1548" height="860" alt="Screenshot 2025-10-21 155515" src="https://github.com/user-attachments/assets/ec7ebcd4-7434-4d36-a9d2-56f171e33a8d" />












## RESULT:
Thus the program to print even numbers ranging from M to N (including M and N values) has been executed successfully
 
 


# EX-07-Nested-loop

## AIM:

Write a C program to print the given triangular Star pattern using loop.

EXAMPLE :

INPUT:

5

OUTPUT :


*****

****

***

**

*

## ALGORITHM:

1.	Declare a variable to store the number of rows in the triangle.
2.	Use the printf function to prompt the user to enter the number of rows.
3.	Use a loop (for or while) to iterate through each row.
4.	Inside the loop, use another loop to print the desired number of asterisks for each row.
5.	Continue the loop until you have printed the entire triangular pattern.

## PROGRAM:
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d ",&n);
    for(i=1;i<=n;i++)
    {
        for(j=n;j>=i;j--)
        {
        printf("*");
        }
        printf("\n");
    }
    return 0;
}


## OUTPUT:
<img width="1458" height="879" alt="Screenshot 2025-10-21 155742" src="https://github.com/user-attachments/assets/212c71aa-71ba-4ec8-aa5e-831f9c0aa3d8" />





## RESULT:

Thus the program to print the given triangular pattern using loop has been executed successfully
 
 


# EX-08-Functions

## AIM:

Write a C program to generate Fibonacci series for given number using function with arguments & without return type.

For example:

Input	Result
15     0 1 1 2 3 5 8 13 21 34 55 89 144 233 377 

## ALGORITHM:

1.	Declare two functions, one for addition and one for subtraction. Both functions should take two integer arguments.
2.	Inside the addition & subtraction function, add & subtract the two numbers and print the result.
3.	In the main function, declare two integer variables and read their values from the user.
4.	Call the addition and subtraction functions, passing the two numbers as arguments.

## PROGRAM:
#include <stdio.h>
void fibonacci(int a);
int main()
{
    int a;
    scanf("%d", &a);
    fibonacci(a);
}

void fibonacci(int a)
{
    int b=0,c=1,d;
    {
       for(int i=0;i<a;i++) 
    
   { printf("%d ", b);
    d=b+c;
   
    b=c;
    c=d;}
    }
    
}


## OUTPUT:

<img width="1504" height="873" alt="Screenshot 2025-10-21 155942" src="https://github.com/user-attachments/assets/b7f520d1-adcd-467e-affb-ce5aae29f8ed" />





## RESULT:

Thus the program to perform addition and subtraction of two numbers using functions has been executed successfully
 
 


# EX-09-Use For Loop

## AIM:

Write a c program to find the sum of even digits using do while loop in a Given range

## ALGORITHM:

1.	Declare variables to store the input number and the sum of odd digits.
2.	Initialize the sum of odd digits to 0.
3.	Use a for loop to iterate through each digit of the input number.
4.	Inside the loop, extract the rightmost digit of the number (using the modulo operator % and division by 10).
5.	If the digit is odd, add it to the sum of odd digits.
6.	Print the sum of odd digits.

## PROGRAM:
#include<stdio.h>
int main()
{
    int a,b,i,total=0;
    scanf("%d %d", &a, &b);
    i=a;
    do
    {
        
        if(i%2==0){
            total+=i;
        }
        i++;
    }while(i<=b);
    printf("%d",total);
    return 0;
}


## OUTPUT:

<img width="1506" height="873" alt="Screenshot 2025-10-21 160146" src="https://github.com/user-attachments/assets/29e6e6b1-07e0-43d9-91c7-8294c14dccac" />



## RESULT:

Thus the program to find the sum of odd digits using for loop has been executed successfully.




# EX – 10 - Factorial of a Number Using a Function
## AIM:
Write a c program to find the sum of odd digits using for loop in a Given range
## ALGORITHM:
1.	Start
2.	Declare the function fact().
3.	In the main() function, call the fact() function.
4.	In fact() function:
a.	Declare variables i, N, and fact (initialized to 1).
b.	Read an integer N from the user.
c.	Use a for loop from 1 to N:
i.	Multiply fact by i in each iteration.
d.	After the loop, print the factorial value.
5.	End

## PROGRAM:
#include<stdio.h>
int main()
{
    int a,b,i,sum=0;
    scanf("%d %d", &a, &b);
    for(i=a;i<=b;i++)
    {
        if(i%2!=0)
        {

            printf("%d  ",i);
            sum=sum+i;
        }
       
    }
    printf("\n%d",sum);
    return 0;
}


## OUTPUT:
<img width="1471" height="880" alt="Screenshot 2025-10-21 160303" src="https://github.com/user-attachments/assets/82f93761-b84d-4a81-af26-d159b29192ba" />



## RESULT:
The program correctly computes the factorial of a given number using a separate function and displays the result.
 
