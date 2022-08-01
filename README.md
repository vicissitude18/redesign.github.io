#define _CRT_SECURE_NO_WARNINGS//用于求1！+2！+...+n！
#include<stdio.h>
int main()
{
  int n=0;
  int i=0;
  int j=0;
   int sum=0;
  scanf("%d",&n);// 用于接收n的值
 for(i=1;i<=n;i++)
 {     int ret=1;
   for(j=1;j<=i;j++)
   {  ret*=j;
   }
   sum+=ret;
 }
 printf("%d\n",sum);
return 0;
}
