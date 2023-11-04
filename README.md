# EX-3(B)        FIBONACCI SERIES

## AIM:
To write a C program to generate the Fibonacci series for the value 

## ALGORITHM:
1. Start the program.
2. Read number of terms to display.
3. Add the previous two terms and store it in new term.
4. Assign 2nd term to 1st term and 3rd term to 2nd term.
5. Repeat steps 3 and 4 n number of times.
6. Display the result.
7. Stop the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
   int n,f,f1=-1,f2=1;
   scanf("%d",&n);
do
{
   f=f1+f2;
   f1=f2;
   f2=f;
   printf("%d ",f);
   n--;
}
while(n>0);
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-03-2b/assets/121418522/5c48986f-baec-4e05-8628-96a4c817f909)

## RESULT:
Thus the program to generate the Fibonacci series for the value 6 has been
executed successfully.
