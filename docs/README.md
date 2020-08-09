
<!------Top Start--------->
<div align="center">
<!--lint ignore no-dead-urls-->
<h2>Awesome Python Coding Snippets :rocket:</h2>

 ![Awesome](https://awesome.re/badge.svg) ![Python Coding](https://img.shields.io/badge/Python-Coding-Snippets) ![Snippets](https://img.shields.io/badge/Snippets-red)

 A List Of Python Coding Snippets. 

<img align='center' src="https://media.giphy.com/media/H1SOl377Sc2eYokLTx/giphy.gif" width='70' >
</div>
<!------Top End--------->




<!-- tabs:start -->
#### ** User Input **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Get Password](#Get-Password)

#### ** Strings **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Reverse String](#Reverse-String)

#### ** List **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

<div>

1. [Transpose A List](#Transpose-A-List)
2. [Most Frequent Elements](#Most-Frequent-Elements)
3. [Grouping Adjacent Elements](#Grouping-Adjacent-Elements)
4. [Remove Duplicate](#Remove-Duplicate )
5. [Create Frozenset List](#Create-Frozenset-List)
</div>


#### ** Tuple **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

<div>

1. [Tuple Unpacking](#Tuple-Unpacking)
</div>


#### ** Set **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>


<div>

1. [Unique Elements](#Unique-Elements)
</div>

#### ** Dictionary **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>


<div>

1. [Merge Dictionaries](#Merge-Dictionaries)
2. [List To Dict](#List-To-Dict)
3. [Inverse Dictionary](#Inverse-Dictionary)
4. [Sort List Of Dict](#Sort-List-Of-Dict)
</div>

<!-- tabs:end -->

<!-- UserInput:start -------------------------------------------------------------------------------------------------->
## User Input
### Get Password
```python
#[Author:Ravishankar]
from getpass import getpass
password = getpass()
print(password)
```
<!-- UserInput:start -------------------------------------------------------------------------------------------------->



<!-- string:start -------------------------------------------------------------------------------------------------->

## Strings

### Reverse String
```python
#[Author:Ravishankar]
text = 'reverse'
print(text[::-1])

#Output : esrever
```
<!-- string:end -->



<!-- list:start --------------------------------------------------------------------------------------------------------------->

## List

### Transpose A List
```python
#[Author:Ravishankar]
lst = [['a', 'b'], ['c', 'd'], ['e', 'f']]
res = list(zip(*lst))
print(res)

#Output : [('a', 'c', 'e'), ('b', 'd', 'f')]
```

### Most Frequent Elements
```python
#[Author:Ravishankar]
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

### Grouping Adjacent Elements
```python
#[Author:Ravishankar]
lst = [1, 2, 3, 4, 5, 6]
groups = lambda lst, n : zip(*([iter(lst)]*n))

g1 = list(groups(lst,3))
print(g1)
# Output : [(1, 2, 3), (4, 5, 6)]

g2 = list(groups(lst,2))
print(g2)
# Output : [(1, 2), (3, 4), (5, 6)]
```
### Remove Duplicate 
```python
#[Author:Ravishankar]
numbers = [1, 2, 3, 2, 4, 2, 1, 4]
result = list(set(numbers))
print(result)
# Output : [1, 2, 3, 4]
```

### Create Frozenset List
```python
#[Author:Ravishankar]
lst = [1,2,3]
lst[2] = 4
lst = frozenset(lst)

# you can not assign lst[2] = 5
print(type(lst),lst)

# Output : <class 'frozenset'> frozenset({1, 2, 4})
```
<!-- list:end -------------------------------------------------------------------------------------------------->



<!-- tuple:start -------------------------------------------------------------------------------------------------->

## Tuple


### Tuple Unpacking
```python
#[Author:Ravishankar]
a,b = (10,20) # Tuple Unpacking
print("a:{}\nb:{}".format(a,b))

# Output  a:10 b:20
```
<!-- tuple:end -------------------------------------------------------------------------------------------------->


<!-- set:start -------------------------------------------------------------------------------------------------->
## Set
### Unique Elements
```python
#[Author:Ravishankar]
a = {1, 1, 2, 3, 4, 5, 6, 3, 3, 4}
print(a)

# Output : {1, 2, 3, 4, 5, 6}
```
<!-- set:end -------------------------------------------------------------------------------------------------->


<!-- dictionary:start -------------------------------------------------------------------------------------------------->

## Dictionary
### Merge Dictionaries
```python
#[Author:Ravishankar]
dict1 = { 'a':2, 'b':3}
dict2 = {'c':5, 'd':5}
result = {**dict1, **dict2}
print(result)

#Output : {'a': 2, 'b': 3, 'c': 5, 'd': 5}  
```



### List To Dict
```python
#[Author:Ravishankar]
lst1 = ['a','b']
lst2 = [1,2]
res = dict(zip(lst1,lst2))
print(res)

#Output : {'a': 1, 'b': 2}
```

### Inverse Dictionary
```python
#[Author:Ravishankar]
numbers = {1: 'one', 2: 'two', 3: 'three', 4: 'four'}
inverse = {v: k for k, v in numbers.items()}
print(inverse)

# Output : {'one': 1,  'two': 2, 'three': 3, 'four': 4}
```

### Sort List Of Dict
```python
#[Author:Ravishankar]
numbers={1:'one',2:'two',3:'three',4:'four'}
inverse={v:k for k,v in numbers.items()}
print(inverse)

#Output:{'one':1,'two':2,'three':3,'four':4}
```
<!-- dictionary:end -------------------------------------------------------------------------------------------------->
