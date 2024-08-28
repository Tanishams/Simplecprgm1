# Simplecprgm1
A simple c program to check if the accepted number is even or odd.

#include <stdio.h>
#include<stdlib.h>
void main()
{
    int x;
    printf("Enter a value:");
    scanf("%d",&x);
    if(x%2==0)
    printf("Value is even ");
    else 
    printf("Value is odd");
}
