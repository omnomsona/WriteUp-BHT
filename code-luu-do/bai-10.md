# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long n, m, temp;
    int ktra = 1;
    temp = 1;
    m = 0;
    do{
        cin >> n;
    }while(n <= 0);
    if(n == 1)
        cout << n << " co dang 5 mu 0";
    else if(n % 100 != 25) ktra =0;
    else while(temp < n){
        m++;
        temp *= 5;
        if(temp == n) ktra = 1;
        else ktra = 0;
    }
    if(!ktra) cout << n << " khong co dang 5 mu m";
    else cout << n << " co dang 5 mu " << m;
    return 0;
}
```

## P/s:
- Sử dụng thêm biến đếm "m" để tính số mũ nếu có.
