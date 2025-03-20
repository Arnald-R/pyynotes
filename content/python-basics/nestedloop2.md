---
title: Nestedloop2
date: 2025-03-20
author: Your Name
cell_count: 19
score: 15
---

```python
#created at 20250125
```


```python
https://www.scientecheasy.com/2022/11/nested-loops-in-python.html/
```


```python
for i in range(6,1,-1):
    for j in range(1,i):
        print(j,' ',end = '')
    print()
```

    1  2  3  4  5  
    1  2  3  4  
    1  2  3  
    1  2  
    1  



```python
for i in range(65,70):
    for j in range(65 , i+1):
        print(chr(i),' ',end = '')
    print()
```

    A  
    B  B  
    C  C  C  
    D  D  D  D  
    E  E  E  E  E  



```python
for i in range(70 ,65, -1):
    for j in range(65,i):
        print(chr(j), '',end = '')
    print()
```

    A B C D E 
    A B C D 
    A B C 
    A B 
    A 



```python
import math
```


```python
x = int(input("enter the value of x:"))
```

    enter the value of x: 12



```python
n = int(input("enter the value of y:"))
```

    enter the value of y: 9



```python
S = 1.0 + x
term = 1
count = 1
while count <= n: # Outer while loop.
    power = math.pow(x, count)
    fact = 1
    for i in range(1, count + 1): # Inner for loop.
        fact = fact * 1
    S = S + (power/count)
    count = count + 1
print('Sum of the series = %.2f'%S)
```

    Sum of the series = 632728757.11



```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


---
**Score: 15**