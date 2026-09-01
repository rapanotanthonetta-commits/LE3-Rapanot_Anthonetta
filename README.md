#include<stdio.h>
int main() {
 char name[50];
 char Section[25];
 int num1, num2;
 
 printf("Anthonetta Rapanot ");
 scanf(" %[^\n]", name);
 printf("BSIT-1R14:");
 scanf(" %[^\n]", Section);
 
 printf("Student Calculator\n");
 printf("Enter First Number:");
 scanf("%d", &num1);
 printf("Enter Second Number:");
 scanf("%d", &num2);
 
 printf("Results\n");
 printf("Addition: %d\n", num1 + num2);
 printf("Subtraction: %d\n", num1 - num2);
 printf("Multiplication: %d\n", num1 * num2);
 printf("Division: %2f\n", (float)num1 / num2);
 
 return 0;
}
