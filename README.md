#include<iostream>
using namespace::std;
int j=0;
int main()
{
	long n=2;
	int x=0; j+=2;
	for(int i=1;i<=n;i++)
	{
		j++;
		for(int m=1;m<=i;m++,j++)
	{
		x=x+i;
		j+=2;
	}
	}
	
	cout<<"整个程序的程序步数为："<<j<<endl;
	cout<<"我所期待的程序步数的结果为"<<1+n+1+n*(0.5*n+1)+n*0.5*n<<endl;
	return 0;
}
