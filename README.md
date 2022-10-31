# Small-calculator-in-C
#include<stdio.h>
int main()

{
	int a,b,n,c,yes,d,f,i;
	printf("first step:-\n");
	printf("to add press 1\n");
	printf("to substract press 2\n");
	printf("to multiply press 3\n");
	printf("to divide press 4\n");
	printf("second step:-\n");
	printf("press enter\n");
	scanf("%d",&n);
	for(i=1;i<2;i++)
	{
	if(n==1||n==2 ||n==3 || n==4)
	{
	printf("enter a number\n");
	scanf("%d",&a);
	printf("enter the second number\n");
	scanf("%d",&b);
	int cal=n;
	switch(cal)
	{
	case 1:
		 c= a+b;
		printf("the value is %d\n",c);
		break;
    case 2:
		 c= a-b;
		printf("the value is %d\n",c);
		break;
	case 3:
		 c= a*b;
		printf("the value is %d\n",c);
		break;
	case 4:
		 c= a/b;
		printf("the value is %d\n",c);
		break;
	}

}
else
{
	printf("error");
	getch();
	return 0;
	
}
}
	


    n="";
	for(;;){
	        yes="";
		printf("do you still want to continue then press 5 if you dont then press any button and then enter\n");
	scanf("%d",&yes);
	if(yes==5)
	{
		printf("Enter a number u want to calculate\n");
		scanf("%d",&d);
			printf("first step:-\n");
	printf("to add press 1\n");
	printf("to substract press 2\n");
	printf("to multiply press 3\n");
	printf("to divide press 4\n");
	printf("second step:-\n");
	printf("press enter\n");
	scanf("%d",&n);
	if(n==1||n==2 ||n==3 || n==4)
	{
	
	switch(n)
	{
		case 1:
		 c= c+d;
		printf("%d",c);
		break;
    case 2:
		 c= c-d;
		printf("%d",c);
		break;
	case 3:
		 c= c*d;
		printf("%d",c);
		break;
	case 4:
		 c= a/b;
		printf("%d",c);
		break;
		
    }
	
}
	else
	{
		printf("error");
		getch();
		return 0;
		}	
		
	}


else
{
	printf("the value is %d",c);
 exit(0);
}
}
n="";


	getch();
	return 0;	
}
