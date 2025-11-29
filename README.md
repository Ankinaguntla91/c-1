include<stdio.h>
#include<stdlib.h>
int main(){
    int*p=malloc(3*sizeof(int));
    printf("malloc:%d %d %d",p[0],p[1],p[2]);
    free(p);
    return 0;
}
#include<stdio.h>
int main()
{
int a=15,b=10,temp;
//swapping values of a and b
temp=a;
a=b;
b=temp;
printf ("a=%d,b=%d\n",a,b);
return 0;
}
