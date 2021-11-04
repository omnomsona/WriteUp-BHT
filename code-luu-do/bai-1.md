## Code:
```
#include<iostream>

using namespace std;

int main(){
    long long x, temp;
    cin >> x;
    temp = x;
    x = x * x;
    x = x * x * temp;
    x = x * x * temp;
    cout << x;
    return 0;
}
```
