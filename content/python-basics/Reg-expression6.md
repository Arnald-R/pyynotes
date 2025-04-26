---
title: Reg-Expression6
date: 2025-04-26
author: Your Name
cell_count: 9
score: 5
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
text = "hello world, hello"
```


```python
# Matches 'hello' as a whole word
matches = re.findall(r'\bhello\b', text)
print(matches)  # Output: ['hello', 'hello']
```

    ['hello', 'hello']



```python
import re
```


```python
text = "Hello World"
```


```python
# Case-insensitive matching
match = re.search(r'hello', text, re.IGNORECASE)
if match:
    print("Match found:", match.group())  # Output: 'Hello'
```

    Match found: Hello



```python

```


---
**Score: 5**