# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in five subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in five subjects.

## Algorithm
1. Start
2. Declare variables: sub1, sub2, sub3, sub4, sub5, total, average, and percentage
3. Read the marks of five subjects from the user
4. Calculate total marks:  
   total = sub1 + sub2 + sub3 + sub4 + sub5
5. Calculate average marks:  
   average = total / 5
6. Calculate percentage:  
   percentage = (total / maximum_total_marks) × 100
7. Display the total, average, and percentage
8. End

## Program:
```
#include <stdio.h>
int main()
{
    float a,b,c,d,e,tot,avg,percent;
    scanf("%f%f%f%f%f",&a,&b,&c,&d,&e);
    tot=a+b+c+d+e;
    avg=tot/5;
    percent=avg*100/100;
    printf("Total marks = %.2f\n",tot);
    printf("Average marks = %.2f\n",avg);
    printf("Percentage = %.2f",percent);
    return 0;
    
}
```

## Output:
![image](https://github.com/user-attachments/assets/51d88773-b762-4566-9cd6-e836783046f2)

## Result:
Thus the program was executed and the output was verified successfully.
