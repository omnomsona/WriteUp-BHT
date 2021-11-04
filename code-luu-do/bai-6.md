# Code:
```
#include<iostream>

using namespace std;

int main(){
    long long i;
    double kqua, e;
    e = 0.000001;
    kqua = 0;
    i = 1;
    while(1.0 / i >= e){
        kqua += 1.0 / i;
        i++;
    }
    cout << kqua;
    return 0;
}
```
