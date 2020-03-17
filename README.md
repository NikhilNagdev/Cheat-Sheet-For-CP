# Cheat-Sheet-For-CP
- [Java](README.md#java)
  - [Collections](README.md#collections)
- [C++](README.md#c++)
  - [Vector](README.md#vector)
  
Java
=======
  ## Collections

C++
=======
  ## Vector
  
  ### Methods
  
  ##### To get the size of the vector
    vector<int> v;
    cout<<v.size();
    
  ##### To sort the vector in ascending order nLogn time
    sort(v.begin(), v.end());
  
  ##### To sort the vector in descending order nLogn time
    sort(v.begin(), v.end(), f);
    ====================================
    bool f(int x, int y){
      return x > y;
    }
    
  ##### To get the element that is greater than or equal to the key
    vector<int>::iterator it = lower_bound(v.begin(), v.end(), key);
    OR
    auto it = lower_bound(v.begin(), v.end(), key);
  ##### To get the element that is greater than key
    vector<int>::iterator it = upper_bound(v.begin(), v.end(), key);
    OR
    auto it = upper_bound(v.begin(), v.end(), key);
