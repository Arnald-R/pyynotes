---
title: Dynamicfunction
date: 2025-04-29
author: Your Name
cell_count: 6
score: 5
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/6.-dynamic-imports
```


```python
#Dynamically import a function from a Module
```


```python

```


```python
import importlib

sqrt_function = getattr(importlib.import_module("math"),"sqrt") 
print(sqrt_function(25))
```

    5.0



```python

```


---
**Score: 5**