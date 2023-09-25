# ReverseNumberandCheckPalindrom
#include<stdio.h>
#include<stdlib.h>
int main(void)
{
	int num=0, rem=0, rev=0;
	system("clear");
	printf("Reverse a number anf check it is a palindrome :");
	printf("Enter the Number:");
	scanf("%d",&num);
	while(num!=0)
	{
		rem=num%10;
		rev=(rev*10)+rem;
		num=num/10;
		
	}
	printf("\nReversed Number: %d",rev);
	printf("\n\n");
	return 0;
	 
}
