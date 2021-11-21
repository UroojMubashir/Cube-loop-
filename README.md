#include<iostream>
using namespace std;
int main()
{

 int my_integer;
 cout<<"\nEnter an integer: ";
 cin>>my_integer;
 cout<<"\nThe following are the cubes of numbers from 1 upto your integer "<<my_integer<<"\n"<<endl;
 for(int i = 1; i<=my_integer;i++)
 {
 	cout<<(i*i*i)<<"  ";
 }
 
 cout<<"\n"<<endl;
  return 0;


}
