#include <stdio.h>

int main() {
    int number, count = 0;

    // Input: Ask the user for the number
    printf("Enter a positive integer: ");
    scanf("%d", &number);

    // Initialize a counter for multiples
    int i = 1;

    // Find and print the first 10 multiples of the given number
    printf("The first 10 multiples of %d are:\n", number);
    while (count < 10) {
        int multiple = number * i;
        printf("%d ", multiple);
        count++;
        i++;
    }

    printf("\n");

    return 0;
}
