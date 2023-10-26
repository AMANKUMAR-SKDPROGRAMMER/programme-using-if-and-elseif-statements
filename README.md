# programme using if and elseif statements
 
#include<stdio.h>
int main()
{
    int marks;
    printf("Enter your marks\n");
    scanf("%d",&marks);

    printf("1.the marks is more than 50 out of 100 \n");
    printf("2.the marks is more then 85 out of 100 \n ");
    printf("3.the marks is more then 95 out of 100 \n");
    printf("4.the marks is full 100 out of 100 \n");
    printf("5.the marsk is less then 50 you fail in exam \n");



    if(marks>45){

        printf("you got a nokia 3310 phone\n");

    }

    else if(marks>85 ){

        printf("you got a redmi smart phone \n");

    }

    else if(marks>95){

        printf("you got a samsung smart phone \n");

    }

    else if(marks == 100){

        printf("you got everything cause you score full marks in exam \n");


    }

    else if(marks<50){

        printf("you fail in exam \n");


    }

    return 0;

    


}