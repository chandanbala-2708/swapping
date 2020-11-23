# swapping
#include<stdio.h>
void main()
{
  int a,b;
  printf("Enter two numbers for swapping:\n ");
  scanf("%d %d",&a,&b);
  printf(" Before swapping the numbers: \t%d %d",a,b);
  a=a+b;
  b=a-b;
  a=a-b;
  printf(" After swapping the numbers: \t%d %d",a,b);
}  
