#include<graphics.h>
#include<conio.h>
int main()
{
	int i,j,gm,gd=DETECT;
	initgraph(&gd,&gm," ");
	
	for(i=100;i<=400;i++)
	{
		for(j=100;j<=102;j++)
		{
			putpixel(i,j,WHITE);
			
		}
	}
	for(i=100;i<=102;i++)
	{
		for(j=100;j<=400;j++)
		{
			putpixel(i,j,WHITE);
			
		}
	}
	for(i=100;i<=400;i++)
	{
		for(j=400;j<=402;j++)
		{
			putpixel(i,j,WHITE);
			
		}
	}
	for(i=400;i<=402;i++)
	{
		for(j=100;j<=400;j++)
		{
			putpixel(i,j,WHITE);
			
		}
	}
	for(i=100;i<=150;i++)
	{
		for(j=150;j<=152;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	
	for(i=150;i<=152;i++)
	{
		for(j=100;j<=150;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	for(i=350;i<=400;i++)
	{
		for(j=150;j<=152;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	for(i=350;i<=352;i++)
	{
		for(j=100;j<=150;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	for(i=100;i<=150;i++)
	{
		for(j=350;j<=352;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	for(i=150;i<=152;i++)
	{
		for(j=350;j<=400;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	for(i=350;i<=400;i++)
	{
		for(j=350;j<=352;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	for(i=350;i<=352;i++)
	{
		for(j=350;j<=400;j++)
		{
			putpixel(i,j,WHITE);
		}
	}
	getch();
	return 0;
	closegraph();
}
