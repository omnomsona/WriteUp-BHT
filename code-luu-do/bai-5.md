# Code:
```
#include<iostream>
#include<math.h>

using namespace std;

int main(){
    long long x, n, i, temp;
    double kqua = 0;
    cin >> x >> n;
    temp = x;
    for(i = 1; i <= n; i++){
        kqua = sqrt(kqua + x);
        x *= temp;
    }
    cout << kqua;
    return 0;
}
```
