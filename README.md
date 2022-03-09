# Codeforces-263A
#include &lt;iostream>   using namespace std;   int main(){   int num[6][6];   for(int i=1;i&lt;=5;i++){     for(int j=1;j&lt;=5;j++){       cin >> num[i][j];       if(num[i][j]==1){         cout &lt;&lt; abs(i-3) + abs(j-3);         break;       }     }   }   return 0; }
