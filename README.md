
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a;
    scanf("%d",&a);
    if(a>0)
    {
        puts("it is positive integer");

    }
    else if(a<0)
    {
        puts("it is negative");

    }
    else
    {
        puts("it is zero");
        return 0;

    }
}
