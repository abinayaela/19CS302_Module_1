# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1.Start the program.

2.Declare variables for principal, rate, simple interest and years.

3.Get the values from the user.

4.Calculate the number of years using the formula:

5.years = (simple interest × 100) / (principal × rate)

6.Display the number of years.

7.Stop the program. 

## Program:
```
#include <stdio.h>

int main()
{
    float p, r, si, y;

    scanf("%f %f %f", &p, &r, &si);

    y = (si * 100) / (p * r);

    printf("%.2f", y);

    return 0;
}

```

## Output:
```
1000
5
500

10.00

```



## Result:
Thus the program was executed and the output was verified successfully.
