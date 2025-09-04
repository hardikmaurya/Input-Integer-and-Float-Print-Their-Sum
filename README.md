# Input-Integer-and-Float-Print-Their-Sum
#include <stdio.h>

int main() {
    int num;
    float decimal;

   printf("Enter an integer: ");
    scanf("%d", &num);

   printf("Enter a float: ");
    scanf("%f", &decimal);

  printf("Sum = %.2f\n", num + decimal);
    return 0;
}
