//# square_using_func.c//
#include<stdio.h>
int main()
{
    int n;
    void sqr(int);
    printf("Enter number:");
    scanf("%d",&n);
    sqr(n);
    return 0;
}
void sqr(int n)
{
    int square;
    square=n*n;
    printf("Square is=%d",square);ss
}
