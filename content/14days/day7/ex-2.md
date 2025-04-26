---
title: Ex-2
date: 2025-04-26
author: Your Name
cell_count: 21
score: 20
---

```python
#created at 20250421
```


```python
#Basic Numpy Arrays
```


```python
print("\n === Basic Numpy Arrays ===")
```

    
     === Basic Numpy Arrays ===



```python
import numpy as np
```


```python
arr1 = np.array([1, 2, 3, 4, 5])
```


```python
arr2 = np.array([[1, 2, 3], [4, 5, 6]])
```


```python
print(f"1D Array: {arr1}")
```

    1D Array: [1 2 3 4 5]



```python
print(f"2D Array:\n{arr2}")
```

    2D Array:
    [[1 2 3]
     [4 5 6]]



```python
print(f"arry shapee:{arr2.shape}")
```

    arry shapee:(2, 3)



```python
print(f" Array Dimensions:{arr2.ndim}")
```

     Array Dimensions:2



```python
#Array Creation Methods
```


```python
print("\n Array Creation Methods ")
```

    
     Array Creation Methods 



```python
zeros = np.zeros((2, 3))
```


```python
ones = np.ones((2,2))
```


```python
random_arr = np.random.rand(3, 3)
```


```python
range_arr = np.arange(0, 10, 2)
```


```python
print(f"zeros:{zeros}")
```

    zeros:[[0. 0. 0.]
     [0. 0. 0.]]



```python
print(f"ones:{ones}")
```

    ones:[[1. 1.]
     [1. 1.]]



```python
print(f"Random:{random_arr}")
```

    Random:[[0.59081775 0.0935357  0.08868859]
     [0.58074852 0.06797903 0.22512338]
     [0.11001029 0.88341247 0.68778503]]



```python
print(f"range:{range_arr}")
```

    range:[0 2 4 6 8]



```python

```


---
**Score: 20**