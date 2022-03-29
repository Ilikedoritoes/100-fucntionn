
#include <stdlib.h>
#include <stdio.h>
#define _CRT_SECURE_NO_WARNINGS

void count(int num1)
{

	int i, num2;
	num2 = num1 / 2;
	for (i = 0; i <= num2; i++)
	{
		printf("%d ", i);
	}
	
}

void main()
{
	int x;
	printf("please enter a number for a counting!\n");
	scanf_s("%d", &x);
	count(x);
}
