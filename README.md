# matrix
This is a program for converting numbers into matrix using 1 dimensional array.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a[3][3];
	int i,j;
	printf("Enter 9 numbers: ");
	for(i=1;i<=3;i++)
	{
		for(j=1;j<=3;j++)
		{
			scanf("%d",&a[i][j]);
		}
	}
	printf("\n \n \n");
	for(i=1;i<=3;i++)
	{
		for(j=1;j<=3;j++)
		{
			printf("%d \t",a[i][j]);
		}
		printf("\n");
	}
}
