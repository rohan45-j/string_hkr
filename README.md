#include <cstdio>
#include <iostream>

using namespace std;


int main() {
 
    int T;
    cin>>T;
     for(int i=0; i<T; i++)
     {
         string s;
         cin>>s;
         for(int j = 0; j<s.length(); j++)
         {
             if(j%2==0)
             {
                 cout<<s[j];
             }
         }
             cout<<" ";
             for(int j = 0; j<s.length(); j++)
             {
                 if(j%2!=0)
                 {
                     cout<<s[j];
                 }
             }
         cout<<endl;
     } 
    return 0;
}
