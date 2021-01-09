//wap to convert lower case to upper case.
#include<stdio.h>
#include<conio.h>
 main()
{
	char ch;	
	printf("\t\t\t\t\t\t\t\n Convert Lower case to upper case.\n");
	printf("\t\t\t Enter character=");
	scanf("%c",&ch);
	if(ch>=97&&ch<=122)
	ch=ch-32;
	printf("%c",ch);
	getch();
}
