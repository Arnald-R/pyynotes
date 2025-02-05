---
title: Json4
date: 2025-02-05
author: Your Name
cell_count: 14
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
from datetime import datetime
```


```python
def default_serializer(obj):
    if isinstance(obj, datetime):
        return obj.isoformat()
    raise TypeError(f"Type {type(obj)} not serializable")
```


```python
data = {"event": datetime(2024, 8, 1, 14, 30)}

json_string = json.dumps(data, default=default_serializer)

print(json_string)  # Output: {"event": "2024-08-01T14:30:00"}
```

    {"event": "2024-08-01T14:30:00"}



```python
import json
```


```python
json_string = '{"name": "Eve", "address": {"city": "New York", "zip": "10001"}}'
data = json.loads(json_string)
```


```python
print(data['address']['city'])  # Output: New York
```

    New York



```python
import json
```


```python
class CustomDecoder(json.JSONDecoder):
    def decode(self, s, **kwargs):
        data = super().decode(s, **kwargs)
        data['name'] = data['name'].upper()  # Modify the 'name' field
        return data
```


```python
json_string = '{"name": "Alice", "age": 30}'
data = json.loads(json_string, cls=CustomDecoder)
```


```python
print(data)  # Output: {'name': 'ALICE', 'age': 30}
```

    {'name': 'ALICE', 'age': 30}



```python

```


---
**Score: 10**