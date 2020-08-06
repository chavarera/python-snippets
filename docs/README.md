
<div align="center">

<!--lint ignore no-dead-urls-->
# Awesome Python Coding Snippets 

![Awesome](https://awesome.re/badge.svg) ![Lint Awesome List](https://img.shields.io/badge/Python-Coding-Snippets)


 A List Of Python Coding Snippets  <a href="//python.org">Python</a>. 

<img align='center' src="https://media.giphy.com/media/GoZvZWZA7Kyfm/giphy.gif" >
</div>
<hr/>

## Contents

- [String](#String)
- [List](#List)
- [Tuple](#Tuple)
- [Set](#Set)
- [Dictionary](#Dictionary)


## Strings
<hr/>

### Reverse String
```python
text = 'reverse'
print(text[::-1])

#Output : esrever
```


## List
<hr/>

### Transpose a List
```python
lst = [['a', 'b'], ['c', 'd'], ['e', 'f']]
res = list(zip(*lst))
print(res)

#Output : [('a', 'c', 'e'), ('b', 'd', 'f')]
```

### Most common occurrence of element
```python
from collections import Counter
lst = [1, 2, 3, 1, 2, 4, 2]
top = lambda lst, k: Counter(lst).most_common(k)

most_2 = top(lst, 2)
print(most_2)
# Output: [(2, 3), (1, 2)]

most_1 = top(lst, 1)
print(most_1)

# Output: [(2, 3)]
```

### Grouping adjacent element
```python
lst = [1, 2, 3, 4, 5, 6]
groups = lambda lst, n : zip(*([iter(lst)]*n))

g1 = list(groups(lst,3))
print(g1)
# Output : [(1, 2, 3), (4, 5, 6)]

g2 = list(groups(lst,2))
print(g2)
# Output : [(1, 2), (3, 4), (5, 6)]
```

## Tuple
<hr/>

### Tuple Unpacking
```python
a,b = (10,20) # Tuple Unpacking
print("a:{}\nb:{}".format(a,b))

# Output  a:10 b:20
```

## Set
<hr/>

### Don't Store Duplicate Values
```python
a = {1, 1, 2, 3, 4, 5, 6, 3, 3, 4}
print(a)

# Output : {1, 2, 3, 4, 5, 6}
```


## Dictionary
<hr/>

### Merge Dictionaries
```python
dict1 = { 'a':2, 'b':3}
dict2 = {'c':5, 'd':5}
result = {**dict1, **dict2}
print(result)

#Output : {'a': 2, 'b': 3, 'c': 5, 'd': 5}  
```



### List to dictionary conversion
```python
lst1 = ['a','b']
lst2 = [1,2]
res = dict(zip(lst1,lst2))
print(res)

#Output : {'a': 1, 'b': 2}
```

### Inverse dictionary
```python
numbers = {1: 'one', 2: 'two', 3: 'three', 4: 'four'}
inverse = {v: k for k, v in numbers.items()}
print(inverse)

# Output : {'one': 1,  'two': 2, 'three': 3, 'four': 4}
```
