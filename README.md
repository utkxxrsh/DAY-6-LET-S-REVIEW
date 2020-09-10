# DAY-6-LET-S-REVIEW
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int t;
    cin>>t;
    int l;
    string str;
    string z;
    string y;
    for(int i=1;i<=t;i++){
        cin>>str;
        l=str.length();
        for(int j=0;j<=l-1;j++){
            if(j%2==0){
                cout<<str[j];

            }
        }
        cout<<" ";
        for(int j=0;j<=l-1;j++){
            if(j%2!=0){
                cout<<str[j];
            }
                    
        }
        cout<<endl;
    }

    return 0;
}
