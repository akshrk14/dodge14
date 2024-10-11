#include<stdio.h>
#include<math.h>
int main()
{
     float h,w,bmi;
     printf("input weight in kilograms\n");
     scanf("%f",&w);
     printf("input height in metres\n");
     scanf("%f",&h);
     bmi=w/(pow(h,2));
     printf("bmi:""%f",bmi);
     return 0;
}
