# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long i, n;
    do{
        cin >> n;
    }while (n < 0);
    i = 0;
    while(i * i <= n){
        if(i * i == n){
            cout << n <<" la so chinh phuong";
            goto kthuc;
        }
        i++;
    }
    cout << n << " khong la so chinh phuong";
kthuc:
    return 0;
}
```
