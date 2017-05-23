# loops
#include<conio.h>
#include<iostream.h>
#include<iomanip.h>
void main()
{
int degrees=0;
double radians;
const double pi=3.1415;
cout.precision(6);
 clrscr();
cout<<"degrees to radians\n";
while(degrees<=360)
{
radians=degrees*pi/180;
cout<<setw(6)<<degrees<<setw(10)<<radians<<endl;
degrees+=10;
}
getch();
}
