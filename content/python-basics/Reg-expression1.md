---
title: Reg-Expression1
date: 2025-04-21
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
text = "The price is 100 dollars."
new_text = re.sub(r'\d+', '200', text)  # Replaces digits with '200'
print(new_text)  # Output: The price is 200 dollars.
```

    The price is 200 dollars.



```python
import re
```


```python
pattern = re.compile(r'\d+')  # Compiled regex pattern
matches = pattern.findall("There are 12 apples and 25 oranges.")
print(matches)  # Output: ['12', '25']
```

    ['12', '25']



```python
import re
```


```python
text = "My name is John and I am 30 years old."
match = re.search(r'(\w+) (\d+)', text)  # Captures name and age
```


```python
if match:
    print("Name:", match.group(1))  # John
    print("Age:", match.group(2))   # 30
```

    Name: am
    Age: 30



```python

```


```python

```


---
**Score: 10**