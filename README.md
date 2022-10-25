# solid-fortnight
#include<bits/stdc++.h>
#include<cmath>
using namespace std;

int main()
{
  int n;
  cin>>n;
  int ans1 = sqrt(n);
  int ans2 = cbrt(n);
  int ans3 = (n*n);
  int ans4 = (n*n*n);
  
  cout<<"The square root of "<< n <<" is " <<ans1;
  cout<<"The cube root of "<< n <<" is " <<ans2;
  cout<<"The square  of "<< n <<" is " <<ans3;
  cout<<"The cube of "<< n <<" is " <<ans4;
  
  return 0;
}
