# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start the program.
2. Input the values of Principal (P), Rate of Interest (R), and Simple Interest (SI).
3. Calculate the number of years using the formula:
   
   Years = (SI × 100) / (P × R)

4. Display the calculated number of years.
5. Stop the program.


## Program:
```
#include <stdio.h>

int main()
{
    float P, R, SI, Years;

    printf("Enter Principal Amount: ");
    scanf("%f", &P);

    printf("Enter Rate of Interest: ");
    scanf("%f", &R);

    printf("Enter Simple Interest: ");
    scanf("%f", &SI);

    Years = (SI * 100) / (P * R);

    printf("Number of Years = %.2f", Years);

    return 0;
}
Developed by: Manimaran B 
RegisterNumber: 212223060148

```

## Output:



## Result:
Thus the program was executed and the output was verified successfully.
