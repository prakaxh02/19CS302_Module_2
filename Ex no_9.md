# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1.Start the program. 
2.Take input of a number num and initialize sum to 0. 
3.Use a do-while loop to extract each digit of num. 
4.Check if the digit is odd; if yes, add it to sum. 
5.Print the sum and end the program.
## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by:Santhosh kumar B 
RegisterNumber:  212223060249
*/
#include <stdio.h>

int main() {
    int num, sum = 0, digit;
    scanf("%d", &num);
    do {
        digit = num % 10;
        if (digit % 2 != 0)
            sum += digit;
        num /= 10;
    } while (num != 0);
    printf("%d\n", sum);
    return 0;
}

```

## Output:
<img width="387" height="169" alt="image" src="https://github.com/user-attachments/assets/b27ec732-e7ae-405e-9d6f-9ae4bf3ba2fc" />




## Result:
Thus the program was executed and the output was verified successfully.
