# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long i, n;
    double tong, x, mau;
    cin >> x >> n;
    tong = x;
    mau = 1;
    for(i = 2; i <= n; i++){
        mau += i;
        x *= x;
        tong += x / mau;
    } 
    cout << tong;
    return 0;
}
```
