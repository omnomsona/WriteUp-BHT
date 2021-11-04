# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long n, tong;
    tong = 0;
    cin >> n;
    while (n < 0){
        cin >> n;
    }
    while (n / 10 != 0){
        tong += n % 10;
        n = n / 10;
    }
    tong += n;
    cout << tong;
    return 0;
}
```
## P/s:
- Code sử dụng phương pháp chia dư cho 10 để lấy từng phần tử cho tới khi không còn lấy được nữa thay vì lặp số lần bằng độ dài số N như lưu đồ.
