# 200-problems-solving
200 problem solving in c program
#include <stdio.h>

int main() {
    // Variables to store three numbers
    int num1, num2, num3;

    // Input from the user
    printf("Enter three numbers:\n");
    printf("Enter the first number: ");
    scanf("%d", &num1);
    printf("Enter the second number: ");
    scanf("%d", &num2);
    printf("Enter the third number: ");
    scanf("%d", &num3);

    // Find the maximum number
    int max = num1;

    if (num2 > max) {
        max = num2;
    }

    if (num3 > max) {
        max = num3;
    }

    // Display the maximum number
    printf("The maximum number is: %d\n", max);

    return 0;
}
