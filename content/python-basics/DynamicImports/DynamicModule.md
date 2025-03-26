---
title: Dynamicmodule
date: 2025-03-26
author: Your Name
cell_count: 4
score: 0
---

```python
#created at 20250210
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/6.-dynamic-imports
```


```python
import importlib
module_name = input("Enter a input module:")
function_name = input("Enter a function name:")

module = importlib.import_module(module_name)
function = getattr(module, function_name)

print(function(5))
```

    Enter a input module: math
    Enter a function name: factorial


    120



```python

```


---
**Score: 0**