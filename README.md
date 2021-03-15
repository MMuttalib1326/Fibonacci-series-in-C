# Fibonacci-series-in-C
C language
#include <stdio.h>

int main()
{
    int n,a=0,b=1,c,i;
    printf("entre a number=");
    scanf("%d",&n);
    {   
        for(i=1;i<=n;i++){
        c=a+b;
        printf("%d ",c);
        a=b;
        b=c;
    }   
    }    
    return 0;
}
