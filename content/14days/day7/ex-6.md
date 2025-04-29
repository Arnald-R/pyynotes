---
title: Ex-6
date: 2025-04-29
author: Your Name
cell_count: 17
score: 15
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
print(f"Head:\n{df.head()}")
```

    Head:
         name  age         city
    0    John   21   coimbatore
    1  Arnald   22     banglore
    2  Antony   21  Tirunelveli



```python
print(f"Description :\n {df.describe()}")
```

    Description :
                  age
    count   3.000000
    mean   21.333333
    std     0.577350
    min    21.000000
    25%    21.000000
    50%    21.000000
    75%    21.500000
    max    22.000000



```python
print(f"info:\n {df.info()}")
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 3 entries, 0 to 2
    Data columns (total 3 columns):
     #   Column  Non-Null Count  Dtype 
    ---  ------  --------------  ----- 
     0   name    3 non-null      object
     1   age     3 non-null      int64 
     2   city    3 non-null      object
    dtypes: int64(1), object(2)
    memory usage: 204.0+ bytes
    info:
     None



```python
print(f"Column:\n {df.columns}")
```

    Column:
     Index(['name', 'age', 'city'], dtype='object')



```python
#Dataframe Indexing
```


```python
print("\n === Dataframe Indexing === ")
```

    
     === Dataframe Indexing === 



```python
print(f"column: \n{df['name']}")
```

    column: 
    0      John
    1    Arnald
    2    Antony
    Name: name, dtype: object



```python
print(f"Select rows:\n{df.loc[0:1]}")
```

    Select rows:
         name  age        city
    0    John   21  coimbatore
    1  Arnald   22    banglore



```python
print(f"Selcet by condition:\n{df[df['age'] > 30]}")
```

    Selcet by condition:
    Empty DataFrame
    Columns: [name, age, city]
    Index: []



```python

```


---
**Score: 15**