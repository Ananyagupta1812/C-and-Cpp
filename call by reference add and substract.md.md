#include <stdio.h>
int add(int *x, int *y)
{
    return (*x + *y);
}
int substract(int *a, int *b)
{
    return (*a - *b);
}

int main()
{
    int a, b;
    printf("Enter value for a:");
    scanf("%d", &a);
    printf("\nEnter value for b:");
    scanf("%d", &b);
    printf("\nSum of a and b is:%d", add(&a, &b));
    printf("\nDifference of a and b is:%d", substract(&a, &b));
    return 0;
}
