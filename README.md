# assignment-4
#include<iostream>
using namespace std;
int main()
  {
   int number, i, count = 0;
   bool is_Prime = true;

   cout << "Enter a number: ";
   cin >> number;

   for (i = 2; i <= number / 2; ++i) {
      ++count;
      if (number % i == 0) {
         isPrime = false;
         count++;
      }
   }

   if (isPrime)
      cout << number << " is a prime number" << endl;
   else
      cout << number << " is not a prime number" << endl;

   cout << "1:Factors of " << number<< " are: ";
   for (i = 1; i <= number; ++i) {
      if (number % i == 0)
         cout << i << " ";
   }

   cout << endl << "2:Number of iterations: " << count << endl;

   return 0;
} 
       }
