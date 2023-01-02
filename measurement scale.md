/* convert the followings 
km to miles 
kgs to pounds
inches to meter
cms to inches 
inches to feet
*/
#include <stdio.h>
int main(){
    int ch;
    float sc,m;
    do{
        printf("\n1)kilometers to miles:");
        printf("\n2)kilograms to ponds:");
        printf("\n3)inches to meters:");
        printf("\n4)centimeters to inches:");
        printf("\n5)inches to feet:");
        printf("\nEnter your choice(1-4):");
        scanf("%d",&ch);

        if(ch<6){
            printf("\nEnter scale to be converted:");
            scanf("%f",&sc);
        }
        switch(ch){
            case 1:
            m=sc*0.62;
            printf("\n%0.2f in miles is:%0.2f",sc,m);
            break;
            
            case 2:
            m=sc*2.2;
            printf("\n%f in pounds is:%f",sc,m);
            break;

            case 3:
            m=sc*0.02;
            printf("\n%f in meters is:%f",sc,m);
            break;

            case 4:
            m=sc*0.39;
            printf("\n%f in inches is: %f",sc,m);
            break;

            case 5:
            m=sc*0.08;
            printf("\n%f in feet is: %f",sc,m);
            break;

            default:
            printf("\nWrong choice");
            }
            printf("\n-------------------------\n");
    }
    while(ch!=6);
    
    return 0;

}
