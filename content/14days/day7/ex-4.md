---
title: Ex-4
date: 2025-04-29
author: Your Name
cell_count: 10
score: 10
---

```python
#created at 20250421
```


```python
import numpy as np
```


```python
#Array Indexing and Slicing
```


```python
print("\n === Array Indexing and Slicing ===")
```

    
     === Array Indexing and Slicing ===



```python
arr1 = np.array([[1, 2, 3],[4, 5, 6],[6, 7, 8]])
```


```python
print(f"Element at (1,1):{arr1[1, 1]}")
```

    Element at (1,1):5



```python
print(f"First row:{arr1[0,:]}")
```

    First row:[1 2 3]



```python
print(f"first column:{arr1[:,0]}")
```

    first column:[1 4 6]



```python
print(f"Subarray:\n{arr1[0:2,1:3]}")
```

    Subarray:
    [[2 3]
     [5 6]]



```python

```


---
**Score: 10**