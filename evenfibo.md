#include <bits/stdc++.h>
 using namespace std;


int main() {
   int x; // x is a variable and is the variable's name!
   std::cin >> x;
    //int zero_even_fibonacci = 0;
   // int first_even_fibonacci = 2;
   // std::cout << zero_even_fibonacci << " " << first_even_fibonacci << std::endl;
   
   int a = 0,b = 2, c =2;
   
   //repeated tasks i.e loops
   
   while (c <= x) {
       long long   c = (4*b + a) ;
       a = b;
       b=c;
       if(c>b) break;
       cout<<c<< " ";
   }
   
   return 0;
}
