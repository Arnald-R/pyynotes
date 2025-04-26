---
title: Ex-5
date: 2025-04-26
author: Your Name
cell_count: 9
score: 5
---

```python
#created at 20250421
```


```python
#BAsic Pandass series
```


```python
print("\n === Basic Pandas Series ===")
```

    
     === Basic Pandas Series ===



```python
import pandas as pd
```


```python
series = pd.Series([1, 2, 3, 4, 5], index=['a', 'b', 'c', 'd', 'e'])
```


```python
print(f"Series:\n {series}")
```

    Series:
     a    1
    b    2
    c    3
    d    4
    e    5
    dtype: int64



```python
print(f"Index:{series.index}")
```

    Index:Index(['a', 'b', 'c', 'd', 'e'], dtype='object')



```python
print(f"Values:{series.values}")
```

    Values:[1 2 3 4 5]



```python

```


---
**Score: 5**