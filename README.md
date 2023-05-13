# assignment-4
#include<iostream>
  using namespace std;
  int main()
  {
  int number,i,factors=0,iterations=0;
  boolean prime=true;
  cout<<"enter any positve number: ";
  cin>>number;
if(number == 0|| number==1)
  {
  prime=false;
  }
  for(i=1;i<=number;i++)
