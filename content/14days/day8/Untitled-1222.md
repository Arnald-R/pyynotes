---
title: Untitled-1222
date: 2025-04-29
author: Your Name
cell_count: 7
score: 5
---

```python
#created at 20250428
```


```python
#password Validation
```


```python
print("\n === Password validation ===")
```

    
     === Password validation ===



```python
import re
```


```python
def validate_password(password):
    #atleaset 8 charcters, 1 uppercase, 1 lowercase, 1 Number
    pattern = r'^(?=.*[A-Z])(?=.[a-z])(?=.*\d).{8,}$'
    return bool(re.match(pattern, password))
    
```


```python
print(f"Valid password: {validate_password('Password123')}")
```

    Valid password: True



```python
print(f"Validate password:{validate_password(
```


---
**Score: 5**