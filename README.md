#include <stdio.h>

int main() {
    char name[] = "Anthonetta Rapanot";
    char section[] = "BSIT-1R14";
    double num1 = 50;
    double num2 = 25;

    printf("Student Calculator\n");
    printf("Student name: %s\n", name);
    printf("Section: %s\n", section);

    printf("\nResults:\n");
    printf("%.0f + %.0f = %.0f\n", num1, num2, num1 + num2);
    printf("%.0f - %.0f = %.0f\n", num1, num2, num1 - num2);
    printf("%.0f * %.0f = %.0f\n", num1, num2, num1 * num2);

    if (num2 != 0) {
        printf("%.0f / %.0f = %.2f\n", num1, num2, num1 / num2);
    } else {
        printf("Division by zero is not allowed.\n");
    }

    return 0;
}
