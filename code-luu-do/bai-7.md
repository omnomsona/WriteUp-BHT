# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long i, a, n, mu3, mu7;
    a = -2;
    mu3 = 3;
    mu7 = 7;
    cin >> n;
    for(i = 2; i<= n; i++){
        mu3 *= 3;
        mu7 *= 7;
        a = 5 * a + 2 * mu3 - 6 * mu7 + 12;
    }
    cout << a;
    return 0;
}
```

## P/s:
- Code sử dụng thêm các biến phụ để tính lũy thừa của 3 và 7.
