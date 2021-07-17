
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
#### ** Join Us **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

[Join Whatsapp Broadcast](https://api.whatsapp.com/send?phone=917507500084&text=Join%20Python%20Snippet%20Updates)

[Share your Code ](https://github.com/chavarera/python-snippets/issues)

[![Linkedin: Ravishankar Chavare](https://img.shields.io/badge/-Ravishankar%20chavare-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ravishankar-chavare-84474a102/)](https://www.linkedin.com/in/ravishankar-chavare-84474a102/)
[![GitHub chavarera](https://img.shields.io/github/followers/chavarera?label=follow&style=social)](https://github.com/chavarera)

#### ** Basic **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Python Version At Runtime](#Python-Version-At-Runtime)

#### ** User Input **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Get Password](#Get-Password)

#### ** Functions **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Dynamic Way To Call Functions](#Dynamic-Way-To-Call-Functions)
2. [Create partial function](#Create-partial-function)

#### ** Variable **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Compare DataTypes](#Compare-DataTypes)
2. [Numbers In Python](#Numbers-In-Python)

#### ** Strings **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Reverse String](#Reverse-String)
2. [ASCII Value Of Character](#ASCII-Value-Of-Character)
3. [Size Of String In Bytes](#Size-Of-String-In-Bytes)
4. [String Combinations](#String-Combinations)
5. [String Formatting](#String-Formatting)
6. [Strings And Bytes To List](#strings-and-bytes-to-list)
7. [Alphabets Digits And Punctuation](#Alphabets-Digits-And-Punctuation)

#### ** List **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

<div>

1. [Transpose A List](#Transpose-A-List)
2. [Most Frequent Elements](#Most-Frequent-Elements)
3. [Grouping Adjacent Elements](#Grouping-Adjacent-Elements)
4. [Remove Duplicate](#Remove-Duplicate )
5. [Create Frozenset List](#Create-Frozenset-List)
6. [Select Random Item](#Select-Random-Item)
7. [Shuffle Items](#Shuffle-Items)
8. [Filter Odd Items Using Filter](#Filter-Odd-Items-Using-Filter)
9. [Select Min Values From Two List](#Select-Min-Values-From-Two-List)
10. [Zip List Of List](#Zip-List-Of-List)
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

#### **Iterable**
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>


<div>

1. [Check Any True Value](#Check-Any-True-Value)
2. [Check All True Value](#Check-All-True-Value)

</div>

#### ** Files **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>
<div>

1. [Read CSV File As Dictionary](#Read-CSV-File-As-Dictionary)
</div>


#### **URL Manipulation**
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Join Two URL](#Join-Two-URL)
2. [Learn URL Terminology](#Learn-URL-Terminology)

<!-- tabs:end -->

#### ** Date Time **
<div><img align='right' src="https://media.giphy.com/media/UtnxCnjWAOL1J6TNUR/giphy.gif" width='300' ></div>

1. [Get A Date After 10 Days](#Get-A-Date-After-10-Days)

<!-- tabs:end -->

<!-- tabs:end -->







## Basic
### Python Version At Runtime
```python
#[Author:Ravishankar]
import sys
version = sys.version_info
print(f'{version.major}.{version.minor}.{version.micro}')

# 3.8.3
```
<!-- UserInput:start -------------------------------------------------------------------------------------------------->

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

## Functions
### Dynamic Way To Call Functions
```python
def add(a,b):
  return a+b

def sub(a,b):
  return a-b
  
def mul(a,b):
  return a*b


select_options = {
  '1':add,
  '2':sub,
  '3':mul
}  

a,b = 5,3
option = input("Operation:")

if select_options.get(option):
  result = select_options[option](a,b)
  print(result)
else:
  print("Invalid Options")
  
'''output
Operation: 3
15
'''
```

### Create partial function
```python
#partial is part of functools function 
from functools import partial

def add(a,b):
    """Simple function to return addition"""
    return a+b

#we freeze one argument and create a partial function
new_func = partial(add,5) 

#now call new_func with single parameter 
#where a==5 will be considerd
print(new_func(5)) # 10
print(new_func(6)) # 11
print(new_func(7)) # 12
```

<!-- Variable:start -------------------------------------------------------------------------------------------------->
## Variable

### Compare DataTypes
```python
#[Author:Ravishankar]
lst = [1,2,3,4]
print(isinstance(lst,list))
# True

a = 1.5
print(isinstance(a,int))
#False

c = 1j
print(isinstance(c,complex))
#True
```

### Numbers In Python
```python
[Author:Ravishankar]
# Integer Numbers
print('Integer')
print(1) # Positive 
print(-1) # Negative

# Float Numbers
print('\nFloat')
print(0.0)
print(10.8)
print(-1.9)

# precision Numbers
print('\nprecision')
print(1.33373783838383833877837) # 1.3337378383838383

# Scientific Numbers
print('\nScientific')
print(1e10) # 10000000000.0

# Infinity Numbers
print('\nInfinity')
print(1e450)

# Complex Numbers
print(1j)
```
<!-- Variable:end -------------------------------------------------------------------------------------------------->


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

### ASCII Value Of Character
```python
#[Author:Ravishankar]
str_a = 'a'
ascii_value = ord(str_a)
print(ascii_value)

#97```python

# [Author : Ravishankar]
# Any : return True only when any one of the element is true.

# using multiple condition in if

(a, b, c) = (1, 0, False)
if a != 0 or b != 0 or c != 0:
    print(True)

# Using any() built in funtion

result = any([a, b, c])
print(result)

# Other Examples

result1 = any([0, True, 5])  # True
result2 = any([0, False, 0.0])  # False
result3 = any([1, 4, 5])  # True
```
```

### Size Of String In Bytes
```python
#[Author:Ravishankar]

text = 'Hello Python'
size = len(text.encode('utf-8'))
print(size)

# 12
```
### String Combinations
```python
from itertools import product
text = 'abc'
result = lambda text: product(text,repeat=len(text))

for i in result(text):
	print("".join(i),end=",")
	
'''Output:
aaa,aab,aac,aba,abb,abc,aca,acb,acc,
baa,bab,bac,bba,bbb,bbc,bca,bcb,bcc,
caa,cab,cac,cba,cbb,cbc,cca,ccb,ccc
'''
# ----[Python World]---------
```

### String Formatting
```python
[Author:Ravishankar]
result = '{0:*^20s}'.format('Project')
print(result)
# ******Project*******

result = '{0:+^20s}'.format('Project')
print(result)
# ++++++Project+++++++

result = '{0:_^30s}'.format('Project')
print(result)
# ___________Project____________
```
### Strings And Bytes To List
```python
#[Author: Ravishankar]
text_str = 'Hello'
text_bytes = b'Hello'

str_list = list(text_str)
print(str_list)
#['H', 'e', 'l', 'l', 'o']

bytes_list = list(text_bytes)
print(bytes_list)
#[72, 101, 108, 108, 111]
```

### Alphabets Digits And Punctuation
```python
#[Author:Ravishankar]
from string import printable

# Get alphabets symbol and numbers
print(printable)

'''output
0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!"#$%&'()*+,-./:;<=>?@[\]^_`{|}~ '''
```
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

### Select Random Item
```python
#[Author:Ravishankar]
from random import choice
colors = ['Red','Blue','Green','Orange','Yello','Cyan']
random_color = choice(colors)
print(random_color)

#Output : Blue
```

### Shuffle Items
```python
#[Author:Ravishankar]
from random import shuffle
colors = ['Red','Blue','Green','Orange','Yello','Cyan']
shuffle(colors)
print(colors)

#Output : ['Yello', 'Red', 'Orange', 'Cyan', 'Blue', 'Green']
```
### Filter Odd Items Using Filter
```python
#[Author:Ravishankar]

lst = [1, 2, 3, 4, 5, 6, 7, 8, 9]
is_odd = lambda a : a%2 != 0
result = list(filter(is_odd,lst))
print(result)

# [1, 3, 5, 7, 9]
```
### Select Min Values From Two List
```python
[Author:Ravishankar]
first  = [1,4,6,3,6]
second = [5,3,4,4,7]
result = list(map(min,first,second))
print(result)
# [1, 3, 4, 3, 6]
```
### Zip List Of List
```python
#similiar to itertools.zip_longest
def zip_longest(*iterables, fillvalue=None):
  max_length = len(max(iterables, key=len))
  for i in range(max_length):
    yield [dict(enumerate(ele)).get(i, fillvalue) for ele in iterables]


# Examples

merges = list(zip_longest('ABCD', 'xy', fillvalue='NA'))
print(merges) # [['A', 'x'], ['B', 'y'], ['C', '-'], ['D', '-']]

merge1 = list(zip_longest(['a', 'b'], [1, 2], [True, False]))
print(merge1) # [['a', 1, True], ['b', 2, False]]

merge2 = list(zip_longest(['a'], [1, 2], [True, False])) 
print(merge2) # [['a', 1, True], [None, 2, False]]))

merge3 = list(zip_longest(['a'], [1, 2], [True, False], fillvalue = '_'))
print(merge3) # [['a', 1, True], ['_', 2, False]]))
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


<!-- Iterable:end -------------------------------------------------------------------------------------------------->
##  Iterable
### Check Any True Value
```python
# [Author : Ravishankar]
# Any : return True only when any one of the element is true.

# using multiple condition in if

(a, b, c) = (1, 0, False)
if a != 0 or b != 0 or c != 0:
    print(True)

# Using any() built in funtion

result = any([a, b, c])
print(result)

# Other Examples

result1 = any([0, True, 5])  # True
result2 = any([0, False, 0.0])  # False
result3 = any([1, 4, 5])  # True
```

### Check All True Value
```python
# [Author:Ravishankar]
# all : returns True when all element of iterable are true

# using multiple condition in if

(a, b, c) = (1, 3, 4)
if a != 0 and b != 0 and c != 0:
    print(True)

# Using any() built in function

result = all([a, b, c])
print(result)

# Other Examples

result1 = all([0, True, 5])  # False
result2 = all([0, False, 0.0])  # False
result3 = all([1, 4, 5])  # True........
```
<!-- Iterable:end -------------------------------------------------------------------------------------------------->

<!-- Files:start -------------------------------------------------------------------------------------------------->
## Files
### Read CSV File As Dictionary
```python
import csv
with open('people.csv') as csv_file:
    data = list(csv.DictReader(csv_file))
print(data)
'''Output
[OrderedDict([('Name', 'Ravi'), ('Gender', 'M'), ('Age', '26')]),
 OrderedDict([('Name', 'Akash'), ('Gender', 'M'), ('Age', '19')]),
 OrderedDict([('Name', 'Rima'), ('Gender', 'F'), ('Age', '30')])]
'''
```
<!-- Files:end -------------------------------------------------------------------------------------------------->

<!-- URL Manipulation:start -------------------------------------------------------------------------------------------------->

## URL Manipulation
### Join Two URL
```python
# [ Author : Ravishankar ]
# Join two URL
from urllib.parse import urljoin

url1 = 'https://www.google.com'
url2 = 'search?channel=fs&client=ubuntu&q=python+tutorial'

full_url = urljoin(url1, url2)
print(full_url)

# https://www.google.com/search?channel=fs&client=ubuntu&q=python+tutorial
```

### Learn URL Terminology
```python
# [ Author : Ravishankar ]
# Learn URL in python
# <scheme>://<netloc>/<path>;<params>?<query>#<fragment>

from urllib.parse import urlparse

url = 'http://www.example.com/index?search=src' # Sample url
parsed_url = urlparse(url) # Parse sample url
scheme = parsed_url.scheme # Scheme : http,https,ftp etc...
domain = parsed_url.netloc # Netloc : network locality first level domain
path = parsed_url.path # Execution path
query = parsed_url.query # Query parameter after ? parts

result = '''scheme  = {},
domain = {},
path = {},
query  = {}'''.format(scheme,
        domain, path, query)
print(result)

'''
scheme  = http,
domain = www.example.com,
path = /index,
query  = search=src
'''
```

<!-- URL Manipulation:start -------------------------------------------------------------------------------------------------->

<!-- Date Time:start -------------------------------------------------------------------------------------------------->
## Date Time
### Get A Date After 10 Days
```python
from datetime import datetime,timedelta
from time import time


# Get today timestamp
today = time() 
dt = datetime.fromtimestamp(today)

#Create timedelta Object
delta = timedelta(days=10) # here you can use months years and days

future_dt = dt + delta # Add Timedelta object in datetime object

# specify Date Format
formats = '%d-%m-%Y'
future_dt = datetime.strftime(future_dt,formats)
current_date = datetime.strftime(dt,formats)

print("Current_date:",current_date,
      "\nFuture_date :",future_dt)
      
'''Output
Current_date: 23-08-2020 
Future_date : 02-09-2020
'''
```
<!-- Date Time:end -------------------------------------------------------------------------------------------------->


### python Keyword List
```
import keyword

# keyword list
print(keyword.kwlist)

'''
['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
'''

# check keyword
print(keyword.iskeyword("True")) #True

print(keyword.iskeyword("print")) #False

```
