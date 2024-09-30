# EX06 - PSEUDORANDOM NUMBER GENERATION

## AIM:
Implementation of Pseudorandom Number Generation Using Standard library
## ALGORITHM:
1. Start the program and import the required libraries.
2. Seed the random number generator using the current time (i.e) rand(time(0));
3. Get the number of random numbers to generate.
4. Pass the value for number of iterations and print the numbers.
5. End the program.
## PROGRAM:
```
NAME: Praveen V
Register Number: 212222233004
```
```
#include <stdio.h>
#include <stdlib.h>  
#include <time.h>    

int main() {
    int n, i;
    
    srand(time(0));

    printf("Enter the number of pseudorandom numbers to generate: ");
    scanf("%d", &n);

    printf("Pseudorandom numbers:\n");

    for (i = 0; i < n; i++) {
        int random_number = rand(); // Generate a random number
        printf("%d\n", random_number);
    }

    return 0;
}
```

## OUTPUT: 
![image](https://github.com/user-attachments/assets/c5fa2cf1-cb90-4524-9358-ba58c12b3302)

## RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library is successful
