---
title: Json3
date: 2025-02-05
author: Your Name
cell_count: 13
score: 10
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
data = {"name": "Charlie", "age": 35}

with open('output.json', 'w') as file:
    json.dump(data, file)
```


```python
import json
```


```python
data = {"name": "Dave", "age": 40}
json_string = json.dumps(data, indent=4)

print(json_string)  
# Output: 
# {
#     "name": "Dave",
#     "age": 40
# }
```

    {
        "name": "Dave",
        "age": 40
    }



```python
import json
```


```python
data = [1, 2, 3, 4, 5]
json_string = json.dumps(data)
```


```python
print(json_string)  # Output: [1, 2, 3, 4, 5]
```

    [1, 2, 3, 4, 5]



```python
import json
```


```python
data = {"greeting": "안녕하세요"}
json_string = json.dumps(data, ensure_ascii=False)

```


```python
print(json_string)  # Output: {"greeting": "안녕하세요"}
```

    {"greeting": "안녕하세요"}



```python

```


---
**Score: 10**