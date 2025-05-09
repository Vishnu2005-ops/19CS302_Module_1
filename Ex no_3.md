# EX 3 C program to find simple interest based on principle, year and rate.
## DATE:
## AIM:
To write a C program to find simple interest based on principle, year and rate.
## DATE:

## Algorithm
1. Start
2. Declare variables: principal, rate, time, and interest
3. Read the values of principal, rate, and time from the user
4. Calculate simple interest using the formula:  
           Interest = (principal × rate × time) / 100
5. Display the interest
6. End
## Program:
```
#include <stdio.h>
int main()
{
    float p,t,r,si;
    scanf("%f%f%f",&p,&t,&r);
    si=(p*t*r)/100;
    printf("Simple Interest = %.2f",si);
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/11d0d81a-7307-4cbc-8780-8e1cfe36aef6)


## Result:
Thus the program was executed and the output was verified successfully.
