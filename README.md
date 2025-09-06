1) Write a program to swap two numbers without using a third variable.



#include<stdio.h>
int main() {
    int a = 3, b = 5;

    a = a + b;  
    b = a - b;  
    a = a - b;  

    printf("a = %d, b = %d\n", a, b);
    return 0;
}


