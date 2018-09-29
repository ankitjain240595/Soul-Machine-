#include<iostream.h>
#include<graphics.h>
#include<conio.h>
#include<math.h>


int main()
{
int gdriver = DETECT, gmode;
initgraph(&gdriver, &gmode, "C:\\TC\\bgi");
double x1=0.0,y1=0.0,z1=0.0,x=0.0,y=0.0,output=0.0,xpow=0.0;
cout<<"enter value of x1";
cin>>x1;
cout<<"enter x power";
cin>>xpow;
cout<<"enter value of y1";
cin>>y1;
cout<<"enter output";
cin>>z1;
for(x=-10;x<10;x++)
{
for(y=-10;y<10;y++)
{
output=pow(x1,xpow)*x+y1*y;
putpixel(x,y,RED);
if(output==z1)
{
cout<<x<<" "<<y<<endl;
putpixel(x+100,y+100,RED);
}
}
}

getch();
closegraph();
return 0;
}