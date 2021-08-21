# 6-stairs-of-0-s-1-s-pattern
This c program prints 6 stairs of 0's &amp;1 's
#include<stdio.h>
int main()
{
	int i,j;
	for(i=0;i<6;++i)
	{
		for(j=0;j<=i;++j)
		{
			printf("01");
		}
		printf("\n");
		
	}
	return 0;
}
