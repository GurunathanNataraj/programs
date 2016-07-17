#include<stdio.h>
#include<conio.h>
void main()
{
int i;
printf("enter the number:");
scanf("%d",&i);
if(i>0)
{
printf("the given number is positive");
}
else if(i<0)
{
printf("the given number is negative");
}
else
{
printf("the given number is zero");
}
getch();
}
