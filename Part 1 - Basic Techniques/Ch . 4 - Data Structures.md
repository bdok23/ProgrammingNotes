#### Dynamic Arrays
Def: *An array whose size can be changed during the execution of a program*

`v.back();` Last element of a vector

`vector <int> v(10, 5);` size 10, initial value is 5 for each element of vector v

#### Set Structures
Def: *A set is a data structure that maintains a collection of elements.*

`set <int> s;`
  
`s.insert(3);` adds s to the set

`s.count(3);` returns the number of times 3 appears in s

`s.erase(3);` removes 3 from the set
  
```
Outputs every element in s
for(auto x:s){ 
  cout << x << "\n";
  }
```
Every element is distinct in a set s.

`multiset <int> s;` allows multiple instances of an element
  
`s.erase(5);` removes all instances of a 5 in the set

`s.erase(s.find(5));` removes 1 instance of a 5 in the set

#### Map Structures
Def: *A map is a generalized array that consits of key-valued-pairs*

`map <string, int> m;` The keys are strings and the values are integers

`m["monkey"] = 4;`

If the value of a key is requested but the map does not contain it, the key is automatically added to the map with a default value.

```
The function count checks if a key exists in a map
if(m.count("yeet")){
  //key exists
  }
```

```
The following code prints all the keys and values in a map:
for (auto x : m) {
  cout << x.first << " " << x.second << "\n";
}
```

#### Iterators and Ranges
Def: *An iterator is a variable that points to an element in a data structure.*

`random_shuffle(v.begin(), v.end());` Randomly shuffles the vector

Same thing works for arrays if you do sort(a, a+n)...

`set <int>::iterator it = s.begin();` Creates an iterator it that points to smallest element in the set

`auto it = s.begin();` also works

#### Bitset
Def: *A bitset is an array whose each value is either 0 or 1.*

`bitset <10> s;` Creates a bitset with 10 elements. 

`s.count();` Returns the number of 1's in the bitset.

#### Deque
Def: *A deque is a dynammic array whose size can be efficiently changed at both ends of the array.*

`deque <int> d;` push_back() - adds element at the end, pop_back() - removes element at the end,

push_front() - adds element at the start, pop_front() - removes first element

#### Stack
Def: *A stack is a data structure that provides two O(1) time operations: adding an element to the top, and removing an element from the top. 

`stack <int> S;` push() - adds element to the end, pop() - removes last element, top() - returns last element

#### Queue
Def: *A queue also provides two O(1) time operations: adding an element to the end of the queue, and removing the first element in the queue. 

`queue <int> q;` push() - adds element to the end, pop() - removes first element in queue, front() - returns last element added

#### Priority Queue
Def: *A priority queue maintains a set of elements.*

`priority_ queue <int> q;` Automatically sorted in decreasing order. 

`.top();` largest element (or first)


















