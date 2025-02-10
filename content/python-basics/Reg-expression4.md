---
title: Reg-Expression4
date: 2025-02-10
author: Your Name
cell_count: 12
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
text = "123abc def 456"
```


```python
# Match digits
digits = re.findall(r'\d+', text)
print("Digits:", digits)  # Output: ['123', '456']
```

    Digits: ['123', '456']



```python
# Match word characters (alphanumeric and underscore)
words = re.findall(r'\w+', text)
print("Words:", words)  # Output: ['123abc', 'def', '456']
```

    Words: ['123abc', 'def', '456']



```python
import re
```


```python
text = "aaabbbcccc"
```


```python
# Matches three 'a's
match = re.search(r'a{3}', text)
if match:
    print("Matched:", match.group())  # Output: 'aaa'
```

    Matched: aaa



```python
# Matches one or more 'b's
match = re.search(r'b+', text)
if match:
    print("Matched:", match.group())  # Output: 'bbb'
```

    Matched: bbb



```python
# Matches between 2 and 4 'c's
match = re.search(r'c{2,4}', text)
if match:
    print("Matched:", match.group())  # Output: 'cccc'
```

    Matched: cccc



```python

```


---
**Score: 10**