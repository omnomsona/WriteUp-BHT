# Code:
```
#include<iostream>

using namespace std;

int main(){
    double x, y, z, a, b, c;
    int can, nhon;
    cin >> x >> y >> z;
    while(x <= 0 || y <= 0 || z <= 0){
        cin >> x >> y >> z;
    }
    if((x + y <= z) || (y + z <= x) || (z + x <= y)){
        cout << "khong phai tam giac";
        goto kthuc;
    }
    if(x == y && y == z){
        cout << "tam giac deu";
        goto kthuc;
    }
    if(x == y || y == z || z == x) can = 1;
    else can = 0;
    a = x * x; b = y * y; c = z* z;
    if(a + b == c || b + c == a || c + a == b){
        cout << "tam giac vuong";
        goto kthuc;
    }
    if((a + b > c) && (b + c > a) && (c + a > b)) nhon = 1;
    else nhon = 0;
    if(nhon){
        if(can) cout << "tam giac nhon can";
        else cout << "tam giac nhon";
    }else if(can) cout << "tam giac tu can";
    else cout << "tam giac tu";
kthuc:
    return 0;
}
```

## P/s:
- Thêm các trường hợp tam giác tù hoặc nhọn.
