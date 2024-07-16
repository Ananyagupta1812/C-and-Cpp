#include <stdio.h>
void star(int rows)
{
    for (int i = 0; i < rows; i++)
    {
        for (int j = 0; j <= i; j++)
        {
            printf("*");
        }
        printf("\n");
    }
}
void reversestar(int rows)
{
    for (int i = 0; i < rows; i++)
    {
        for (int j = 0; j <= rows-i-1; j++)
        {
            printf("*");
        }
        printf("\n");
    }
}
int main()
{
    int rows, ch;
    do
    {
        printf("\n1. Triangular star patter \n2. Reversed triangular star pattern \n3.Exit");
        printf("\nEnter your choice(0-2):");
        scanf("%d", &ch);
        if (ch == 0)
        {
            printf("\nTriangular star patter---");
            printf("\nEnter number of rows:");
            scanf("%d", &rows);
        }
        else if (ch == 1)
        {
            printf("\nReverse triangular star patter---");
            printf("\nEnter number of rows:");
            scanf("%d", &rows);
        }
        switch (ch)
        {
        case 0:
            star(rows);
            break;

        case 1:
            reversestar(rows);
            break;

        case 2:
            return 0;
            break;

        default:
            printf("\nWrong choice");
            break;
        }
        printf("\n---------\n");
    } while (ch != 2);
    return 0;
}
