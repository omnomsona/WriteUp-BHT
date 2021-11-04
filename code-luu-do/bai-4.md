# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long x, n, temp, kqua, i;
    cin >> x >> n;
    kqua = 0;
    x *= x;
    temp = 1;
    for(i = 1; i <= n; i++){
        temp *= -x;
        kqua += temp;
    } 
    cout << kqua;
    return 0;
}
```

## P/s:
- Code sử dụng cách nhân "-x" sau mỗi lần lặp thay vì xét chẵn lẻ như lưu đồ.
