# EX 39 C program to find sum of digits.
:
## AIM:
To write a C program to find sum of digits.

## Algorithm
Start. Define a variables. Write a program to print the English word corresponding to the given number. Read the value using scanf. Ask the user to make an input. Print out the answer. End

## Program:
```
/*
C program to find sum of digits.
Developed by: DUDEKULA HASEENA
RegisterNumber: 212222063004
#include<stdio.h>
int main()
{
    int a,s,i,y=0;
    scanf("%d",&a);
    for(i=1;i<=5;i++)
    {
        s=a%10;
        y=y+s;
        a=a/10;
    }
    printf("%d",y);
}
*/
```

## Output:

<img width="1127" height="167" alt="image" src="https://github.com/user-attachments/assets/d74cc279-d719-413f-b40a-183beac69a33" />


## Result:
Thus the program was executed and the output was verified successfully.
