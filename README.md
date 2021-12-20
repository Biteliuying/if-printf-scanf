# if-printf-scanf
scanf("%d",&amp;a);
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>

int main()
{
	int a;
	printf("请输入出生年份\n");
	scanf("%d",&a);
	int b = 2021 - a;
	if (b < 18)
	{
		printf("未成年\n");
	}
	else
	{
		printf("成年人\n");
	}
	return 0;
}
