#include<stdio.h>
int gcd(int a,int b){
if(b==0)
return a;
else
return gcd(b,a%b);
}
int main(){
int num1,num2;
printf(“25331a05d7\n”);
printf("enter 2 numbers:");
scanf("%d %d",&num1,&num2);
printf("gcd = %d\n",gcd(num1,num2));
return 0;
}


