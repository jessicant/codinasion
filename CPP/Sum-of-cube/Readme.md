## Write a programme to find sum of cube of 'n' number.

```
Input: 4
Output: 100
```

---

```C++
#include<iostream>
using namespace std;
int main(){
    int a,total=0;
    cout<<"Input: ";
    cin>>a;
    for(int i=1 ; i<=a ; i++){
        total += (i*i*i);
    }
    cout<<"Output: "<<total;
    return 0;
}
```