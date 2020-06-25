`sort(v.begin(), v.end());` Sort a vector/string

`sort(v.rbegin(), v.rend());` Sort in reverse

`sort(a, a+n);` Sort array

`tuple <int, int, int>` Another datatype

#### User Defined Structs
```
struct P{
  int x, y;
  bool operator <(const P &p){
    if(x! = p.x) return x < p.x;
    else return y < p.y;
    }
    };
```
`sort(v.begin(), v.end(), comp);` Where comp is user defined sort function

We can use binary search to see when a function changes.
