# program-to-demonstrate-incrementing-and-decrementing-a-pointer

#include<iostream> 
  using namespace std;
   int main(){
       int a=10;
       int *p=&a;

     cout<<"the value of a : "<<a<<"\n";

       (*p)++;
       cout<<"the value of a after increment : "<<a<<"\n";

       (*p)--;
       cout<<"the value of a after decrement :  "<<a;

       return 0;
   }
