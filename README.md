#  location of x or y 
 a program which show the location of x or y or when the value of x is ‘7’ Or value of y is ‘11’ it will show a message “you found a treasure”
 #include<iostream>
#include<conio.h>
using namespace std;
int main()
{
char dis='a';
int x=10,y=10;
cout<<"type enter to quite"<<endl;
cout<<"press direction keys(n,s,e,w)"<<endl;
while(dis!='\r')
{
cout<<"\nyour locatio is"<<x<<","<<y<<endl;
dis=getche();
if(dis=='n')
y++;
else if(dis=='s')
y--;
else if(dis=='e')
x++;
else if(dis=='w')
x--;
if(x==7&&y==11)
cout<<"\n\a*****[you found a treasure]******"<<endl;
}
return 0;
}

