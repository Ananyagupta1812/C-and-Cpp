//using functions without argument and without return value
#include<stdio.h>
int fibonacciseries();
int main(){
    fibonacciseries();
    return 0;
}
int fibonacciseries(){
    int n,limit,first=0,second=1,result;
    printf("Enter limit:");
    scanf("%d",&limit);
    printf("The fibonacci series is\n" );
    for(int i=0;i<=limit;i++){
        if(i<=1){
            result=i;
            //break;
        }
        else{
        result=first+second;
        first=second;
        second=result;
       // break;
        }
        printf("%d\n",result);
    }
    return 0;
}
