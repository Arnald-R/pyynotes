---
title: Nestedloop1
date: 2025-04-21
author: Your Name
cell_count: 17
score: 15
---

```python
#created at 20250125
```


```python
https://www.scientecheasy.com/2022/11/nested-loops-in-python.html/
```


```python
for i in 1,2:
    print("value of i in: ",i)
    for j in 1,2:
        print("value of j in: ",j)
print("nested loop ends here")
```

    value of i in:  1
    value of j in:  1
    value of j in:  2
    value of i in:  2
    value of j in:  1
    value of j in:  2
    nested loop ends here



```python
x = 3
```


```python
y = 5
```


```python
while x < 5:
    print("x value in: ", x)
    while y < 10:
        print("y value in: ",y)
        y += 1
    x += 1
print("nested while ends here")
```

    x value in:  3
    y value in:  5
    y value in:  6
    y value in:  7
    y value in:  8
    y value in:  9
    x value in:  4
    nested while ends here



```python
print("math table of '6'")
```

    math table of '6'



```python
for i in range  (6,7):
    for j in range(1 , 11):
        x = i * j
        print(i ,'*', j,' = ',x)
    print()
print("loop ended")
```

    6 * 1  =  6
    6 * 2  =  12
    6 * 3  =  18
    6 * 4  =  24
    6 * 5  =  30
    6 * 6  =  36
    6 * 7  =  42
    6 * 8  =  48
    6 * 9  =  54
    6 * 10  =  60
    
    loop ended



```python
x = 1
```


```python
while x <=5 :
    tot,y = 1,1
    print()
    while y <= 10:
        tot = x * y
        print( x ,'*', y ,'=' ,tot)
        y = y+1
    x = x + 1
print(" nested loop winded up")
```

    
    1 * 1 = 1
    1 * 2 = 2
    1 * 3 = 3
    1 * 4 = 4
    1 * 5 = 5
    1 * 6 = 6
    1 * 7 = 7
    1 * 8 = 8
    1 * 9 = 9
    1 * 10 = 10
    
    2 * 1 = 2
    2 * 2 = 4
    2 * 3 = 6
    2 * 4 = 8
    2 * 5 = 10
    2 * 6 = 12
    2 * 7 = 14
    2 * 8 = 16
    2 * 9 = 18
    2 * 10 = 20
    
    3 * 1 = 3
    3 * 2 = 6
    3 * 3 = 9
    3 * 4 = 12
    3 * 5 = 15
    3 * 6 = 18
    3 * 7 = 21
    3 * 8 = 24
    3 * 9 = 27
    3 * 10 = 30
    
    4 * 1 = 4
    4 * 2 = 8
    4 * 3 = 12
    4 * 4 = 16
    4 * 5 = 20
    4 * 6 = 24
    4 * 7 = 28
    4 * 8 = 32
    4 * 9 = 36
    4 * 10 = 40
    
    5 * 1 = 5
    5 * 2 = 10
    5 * 3 = 15
    5 * 4 = 20
    5 * 5 = 25
    5 * 6 = 30
    5 * 7 = 35
    5 * 8 = 40
    5 * 9 = 45
    5 * 10 = 50
     nested loop winded up



```python
print("tables from 1 - 5")
```

    tables from 1 - 5



```python
for i in range (1,6):
    for j in range (1,11):
        tot = i * j
        print(i,'*',j ,'=',tot)
    print()
```

    1 * 1 = 1
    1 * 2 = 2
    1 * 3 = 3
    1 * 4 = 4
    1 * 5 = 5
    1 * 6 = 6
    1 * 7 = 7
    1 * 8 = 8
    1 * 9 = 9
    1 * 10 = 10
    
    2 * 1 = 2
    2 * 2 = 4
    2 * 3 = 6
    2 * 4 = 8
    2 * 5 = 10
    2 * 6 = 12
    2 * 7 = 14
    2 * 8 = 16
    2 * 9 = 18
    2 * 10 = 20
    
    3 * 1 = 3
    3 * 2 = 6
    3 * 3 = 9
    3 * 4 = 12
    3 * 5 = 15
    3 * 6 = 18
    3 * 7 = 21
    3 * 8 = 24
    3 * 9 = 27
    3 * 10 = 30
    
    4 * 1 = 4
    4 * 2 = 8
    4 * 3 = 12
    4 * 4 = 16
    4 * 5 = 20
    4 * 6 = 24
    4 * 7 = 28
    4 * 8 = 32
    4 * 9 = 36
    4 * 10 = 40
    
    5 * 1 = 5
    5 * 2 = 10
    5 * 3 = 15
    5 * 4 = 20
    5 * 5 = 25
    5 * 6 = 30
    5 * 7 = 35
    5 * 8 = 40
    5 * 9 = 45
    5 * 10 = 50
    



```python
print("triangle of *")
```

    triangle of *



```python
for i in range (1,6):
    for j in range( 1,i+1):
        print('*',end = '')
    print()
```

    *
    **
    ***
    ****
    *****



```python
print("truangle of numbers:")
```

    truangle of numbers:



```python
for i in range (1,6):
    for j in range(1,i+1):
        print(j,' ',end = '')
    print()
```

    1  
    1  2  
    1  2  3  
    1  2  3  4  
    1  2  3  4  5  



```python

```


---
**Score: 15**