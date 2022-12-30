// write a program to check whether an integer is Armstrong or not
#include <stdio.h>
#include <math.h>

int main()
{
    int a,m,p,s,sum=0;
    printf("Enter any number:"); 
    scanf("%d",&a);
    p=a;
    //printf("The orginal number is:%d",a);
    while(a>0)
    {
        m=a%10;
        s=m;
        a=a/10;
        sum=pow(s,3)+sum;
    }
    printf("%d\n",sum);
    if(p==sum){
        printf("%d is an Armstrong number",sum);

    }
    else{
        printf("%d is  not an Armstrong number",sum);
    }

    return 0;

}
