# C-Programming
#include<stdio.h>
int main()
{
	int i=1,fact=1,n;
	printf("\n Enter the value of n");
	scanf("%d",&n);
	for(i=1;i<=n;i++)
	{
	fact=fact*i;
	}
	printf("\n The factorial of n =%d",fact);
	return 0;
}
