
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