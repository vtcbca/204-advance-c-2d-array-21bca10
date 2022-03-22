#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
 void prime();
 void palindrome(int);
 //int reverse();
 //int even(int);
 int menu();
 void main()
{
	int c,x,even;
	char yn;
	clrscr();
	do
	{
	 c=menu();
	  switch(c)
		{
		case 1: prime();
			break;
		case 2:
			printf("\nEnter Number: ");
			scanf("%d",&x);
			palindrome(x);
			break;
	       /*	case 3:
			printf("\nEnter any Valur: ");
			reverse();
			break;
			case 4:
			printf("\nEnter any value:  ");
			scanf("%d",&x);
			even(x);
			printf("Even number is %d",x);
			break;*/
		case 5:
			break;
		case 6:
			exit(0);
		default:
			printf("\nEnter valide Number");
		}
	printf("\n\nDo you want to Continue ??(yes=Y/y||No=N/n):");
	flushall();
	scanf("%c",&yn);
	}
	while(yn=='y'||yn=='Y');
}
int menu()
{
	int choice;
	printf("\nMenu");
	printf("\n----------------------------");
	printf("\n1.Prime Number\n2.Palindrome Number\n3.Print Number in Reverse\n4.Even Number series\n5. \n6.Exit");
	printf("\n----------------------------");
	printf("\nEnter Your Choice: ");
	scanf("%d",&choice);
	return(choice);
}
void prime()
{
	int x,y,z=0;
	printf("\nEnter any Number: ");
	scanf("%d",&x);
	y=2;
	while(y<=x/2)
	{
	 if(x%y==0)
	   {
		z=1;
		break;
	   }
	 y++;
	}
	if(z==0)
	{
		printf("\nYour Number is Prime",x);
	}
	else
	{
		printf("\nYour Number is Not Prime",x);
	}
}
void palindrome(int a)
{
	int x,y,z,sum=0;
	z=x;
	while(x>0)
	{
		y=x%10;
		sum=(sum*10)+y;
		x=x/10;
	}
	if(z==sum)
		printf("\nYour Number is Palindrome");
	else
		printf("\nYour Number is Not Palindrome");
