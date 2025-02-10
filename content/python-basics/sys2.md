---
title: Sys2
date: 2025-02-10
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250204
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/pythons-sys-module
```


```python
import sys

print(f"Python version: {sys.version}")
```

    Python version: 3.12.8 | packaged by Anaconda, Inc. | (main, Dec 11 2024, 16:31:09) [GCC 11.2.0]



```python
import sys

# Print current sys.path
print("Before modifying sys.path:", sys.path)

# Add a new path
sys.path.append('/path/to/directory')

# Print updated sys.path
print("After modifying sys.path:", sys.path)
```

    Before modifying sys.path: ['/home/arnald/miniconda3/envs/py312/lib/python312.zip', '/home/arnald/miniconda3/envs/py312/lib/python3.12', '/home/arnald/miniconda3/envs/py312/lib/python3.12/lib-dynload', '', '/home/arnald/miniconda3/envs/py312/lib/python3.12/site-packages']
    After modifying sys.path: ['/home/arnald/miniconda3/envs/py312/lib/python312.zip', '/home/arnald/miniconda3/envs/py312/lib/python3.12', '/home/arnald/miniconda3/envs/py312/lib/python3.12/lib-dynload', '', '/home/arnald/miniconda3/envs/py312/lib/python3.12/site-packages', '/path/to/directory']



```python
import sys
```


```python
a = [1, 2, 3]
size = sys.getsizeof(a)
print(f"Size of list 'a': {size} bytes")
```

    Size of list 'a': 88 bytes



```python
import sys

print("This is a normal message.")
print("This is an error message.", file=sys.stderr)
```

    This is a normal message.


    This is an error message.



```python

```


---
**Score: 5**