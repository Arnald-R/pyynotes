---
title: Json1
date: 2025-04-29
author: Your Name
cell_count: 9
score: 5
---

```python
#created at 20250204
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/handling-json-data
```


```python
import json
```


```python
json_string = '{"name": "Alice", "age": 30}'
parsed_data = json.loads(json_string)

print(parsed_data)  # Output: {'name': 'Alice', 'age': 30}
```

    {'name': 'Alice', 'age': 30}



```python
import json
```


```python
data = {"name": "Bob", "age": 25}
json_string = json.dumps(data)

print(json_string)  # Output: {"name": "Bob", "age": 25}
```

    {"name": "Bob", "age": 25}



```python
import json
```


```python
with open('data.json', 'r') as file:
    data = json.load(file)

print(data)  # Output will depend on the content of 'data.json'
```


    ---------------------------------------------------------------------------

    FileNotFoundError                         Traceback (most recent call last)

    Cell In[8], line 1
    ----> 1 with open('data.json', 'r') as file:
          2     data = json.load(file)
          4 print(data)  # Output will depend on the content of 'data.json'


    File ~/miniconda3/envs/py312/lib/python3.12/site-packages/IPython/core/interactiveshell.py:324, in _modified_open(file, *args, **kwargs)
        317 if file in {0, 1, 2}:
        318     raise ValueError(
        319         f"IPython won't let you open fd={file} by default "
        320         "as it is likely to crash IPython. If you know what you are doing, "
        321         "you can use builtins' open."
        322     )
    --> 324 return io_open(file, *args, **kwargs)


    FileNotFoundError: [Errno 2] No such file or directory: 'data.json'



```python

```


---
**Score: 5**