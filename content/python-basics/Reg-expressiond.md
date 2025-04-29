---
title: Reg-Expressiond
date: 2025-04-29
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250204
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/regular-expressions-with-re
```


```python
import re
```


```python
# re.match() example
result = re.match(r'hello', 'hello world')
if result:
    print("Match found:", result.group())
else:
    print("No match")

```

    Match found: hello



```python
# re.search() example
result = re.search(r'world', 'hello world')
if result:
    print("Search found:", result.group())
else:
    print("No search match")
```

    Search found: world



```python
import re
```


```python
text = "The quick brown fox jumps over the lazy dog."
matches = re.findall(r'\b\w{3}\b', text)  # Matches words of exactly 3 letters
print(matches)  # Output: ['The', 'fox', 'the', 'dog']
```

    ['The', 'fox', 'the', 'dog']



```python

```


---
**Score: 5**