# project-on-array-pointer
#c++ program to ccess the elements of an array using pointer 
#include<iostream>
using namespace std;
int main()
{
	int *p;
	int arr[] = {2,3,5,4};
	p = arr;
	for(int i=0;i<4;i++)
	{
		cout<<*p<<endl;
		p++;
	}
	return 0;
}
