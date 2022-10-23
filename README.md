# Study
the road of learning
#include<stdio.h>
int main()
{
	int i = 0;
	int n = 0;
	int b = 1;
	scanf_s("%d",& n);
	for (i = 1; i <= n; i++)
	{
		b = b * i;
	}
	printf("%d", b);
	return 0;
}
