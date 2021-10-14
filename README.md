#include<stdio.h>
int main()
{
    //display the cases
    printf("enter the choice:");
    int choice=0;
    scanf("%d",&choice);
    switch(choice)
    {
        case 1:
        printf("grade obtained by the student is A");
        break;
        case 2:
        printf("grade obtained by the student is B");
        break;
        case 3:
        printf("grade obtained by the student is C");
        break;
        case 4:
        printf("grade obtained by the student is D");
        break;
        default:
        printf("invalid choice");
    }
}
