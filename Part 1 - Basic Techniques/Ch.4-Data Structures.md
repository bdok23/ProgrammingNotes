## Dynamic Arrays
An array whose size can be changed during the execution of a program
v.back() //last element of a vector
vector <int> v(10, 5); //size 10, initial value is 5 for each element of vector v

Set Structures:
set <int> s;
s.insert(3); //adds s to the set
s.count(3); // returns the number of times 3 appears in s
s.erase(3); //remves 3 from the set
for(auto x:s){  //outputs every element in s
  cout << x << "\n";
  }
Every element is distinct in a set s.
multiset <int> s; //allows multiple instances of an element
s.erase(5); //removes all instances of a 5 in the set
s.erase(s.find(5)); //removes 1 instance of a 5 in the set

Map Structures:
A map is a generalized array that consits of key-valued-pairs
map <string, int> m; //The keys are strings and the values are integers
m["monkey"] = 4;
If the value of a key is requested but the map does not contain it, the key is automatically added to the map with a default value.
if(m.count("yeet")){  //The function count checks if a key exists in a map
  //key exists
  }
The following code prints all the keys and values in a map:
for (auto x : m) {
  cout << x.first << " " << x.second << "\n";
}



























