# suffix_trees
Python implementation of Suffix Trees and Generalized Suffix Trees. Provided also methods with typcal aplications of STrees and GSTrees. 

### Usage

```python
from STree import STree

# Suffix-Tree example.
st = STree("abcdefghab")
print(st.find("abc")) # 0
print(st.find_all("ab")) # [0, 8]

# Generalized Suffix-Tree example.
a = ["xxxabcxxx", "adsaabc", "ytysabcrew", "qqqabcqw", "aaabc"]
st = STree(a)
print(st.lcs()) # "abc"
```


### Usage

number of sub nodes of a certain node
```
print(len(node.transition_links))
```

check whehter a node is leave node
```
print(node.is_leaf())
```


### Others
read ```_build_naive()``` and ```find()``` of STree.py would be very helpful for understanding.




