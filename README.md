# string-reversal
#include<iostream>
#include<cstring>
using namespace std;
int main()
{
 string str="crack";
 string rev="";
 int i;
 for(i=str.size()-1;i>=0;i--)
  {
   rev=rev+str[i];
   cout<<rev<<endl;
  }
 if(str==rev)
  {
   cout<<"palindrome"<<endl;
  }
 else
  {
   cout<<"not pallindrome"<<endl;
  }
 return 0;
 
}
