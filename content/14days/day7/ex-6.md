---
title: Ex-6
date: 2025-04-21
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250421
```


```python
#Creating Dataframe
```


```python
import pandas as pd
```


```python
print("\n === Dataframe Creation ===")
```

    
     === Dataframe Creation ===



```python
data = {
    'name' : ['John', 'Arnald', 'Antony'],
    'age':[21, 22, 21],
    'city':['coimbatore', 'banglore', 'Tirunelveli']
}
```


```python
df = pd.DataFrame(data)
```


```python
print(f"Dataframe:\n{df}")
```

    Dataframe:
         name  age         city
    0    John   21   coimbatore
    1  Arnald   22     banglore
    2  Antony   21  Tirunelveli



```python
#
```


---
**Score: 5**