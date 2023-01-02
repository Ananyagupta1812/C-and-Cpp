// write a program to check whether an integer is prime or not
#include <stdio.h>
#include <math.h>

int main()
{
    int n;
    printf("enter any number:");
    scanf("%d",&n);
    for(int i=2;i<n/2;i++){
        if(n%i==0){
            printf("%d is not prime\n",n);
            break;
        }
        else{
            printf("%d is prime",n);  
            break;
        }
    }
    return 0;
}


// using functions
#include <stdio.h>
#include <math.h>
int checkprime();

int main()
{
    checkprime();
    return 0;    
}
int checkprime(){
    int n;
    printf("enter any number:");
    scanf("%d",&n);
    for(int i=2;i<n/2;i++){
        if(n%i==0){
            printf("%d is not prime\n",n);
            break;
        }
        else{
            printf("%d is prime",n);  
            break;
        }
    }
    return 0;
}





