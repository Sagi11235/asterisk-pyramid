# asterisk-pyramid
C++ code that get an odd number and paint an asterisk pyramid of the fitting size

#include <iostream>
using namespace std;
int main() {
    int n;
    cout<<"Enter an odd number \n";
    cin>>n;
    for (int j=1;j<=n;j=j+2){
        for (int i=0;i<n-j;i++){
            cout<<" ";
        }
        for (int i=0;i<j;i++){
            cout<<"* ";
        }
        cout<<"\n";
    }
    return 0;
}
