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
{
  iterations++
  if (number % i ==; 0)
  cout<<i<<" "<<endl;
factors ++;
  }
  }
if (prime)
{
cout<<number<<" a prime number"<<endl;
  }
  else
  {
   cout<<number<<" is a composite number"<<endl;
    }
    cout<<" number of factors: "<<factors<<endl;
    cout<<" number of iterations: "<<iterations<<endl;
     return 0;
       }
