// write a program to revrese an integer
#include <stdio.h>

int main()
{
    int a,m,s=0;
    printf("Enter any number:");
    scanf("%d",&a);
    printf("The orginal number is:%d",a);
    while(a>0)
    {
        m=a%10;
        s=s*10+m;
        a=a/10;
    }
    printf("\nreversed number is:%d",s);
    return 0;

}
