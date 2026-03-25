# M1-D4
AIM:
Write a C program to check whether number which are multiples  of 5 is divisible by 10 or not using nested if.
PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a%5==0)
    {
        printf("The number is multiples of 5");
        if (a%10==0)
        {
            printf("\nThe number is also divisible by 10");
        }
        else
        {
            printf("\nThe number Not divisible by 10");
        }
    }
    else
    {
       printf("The number is NOT an multiples of 5");
    }
}
```
OUTPUT:
<img width="1033" height="389" alt="image" src="https://github.com/user-attachments/assets/3b2e3651-2979-41c0-8295-5e244e8f2a1a" />

RESULT:
Thus the code run successfully!
