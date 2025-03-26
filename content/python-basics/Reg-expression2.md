---
title: Reg-Expression2
date: 2025-03-26
author: Your Name
cell_count: 11
score: 10
---

```python
#created at 20250203
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/regular-expressions-with-re
```


```python
import re
```


```python
text = "hello world"
```


```python
# Matches 'hello' at the start of the string
if re.match(r'^hello', text):
    print("Starts with 'hello'")
```

    Starts with 'hello'



```python
# Matches 'world' at the end of the string
if re.search(r'world$', text):
    print("Ends with 'world'")
```

    Ends with 'world'



```python
import re
```


```python
text = "apple,banana,orange"
fruits = re.split(r',', text)  # Split by comma
print(fruits)  # Output: ['apple', 'banana', 'orange']
```

    ['apple', 'banana', 'orange']



```python
import re
```


```python
text = "abc def"
match = re.search(r'a.b', text)
if match:
    print("Pattern found:", match.group())  # Output: 'abc'
```


```python

```


---
**Score: 10**