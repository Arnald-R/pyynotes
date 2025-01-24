---
title: If-Statement2
date: 2025-01-24
author: Your Name
cell_count: 18
score: 15
---

```python
#created at 20250123
```


```python
https://www.scientecheasy.com/2022/10/if-statement-in-python.html/
```


```python
num = int(input("Enter the number: "))
```

    Enter the number:  34



```python
if num % 2 == 0:
    print(num, "is an even number")
```

    34 is an even number



```python
if num % 2 != 0:
    print(num, "is odd number")
```


```python
# Read the number from the user to check even or odd.
num = int(input("Enter a number: "))
if num % 2 == 0:
    print(num, 'is an even number')
if num % 2 != 0:
    print(num, 'is a odd number')

```


```python
x, y, z =20, 40, 50
```


```python
if((y > x) and ( y < z)):
    print("y is greater than x but smaller than z")
```

    y is greater than x but smaller than z



```python
if((x > y) and (y < z)):
    print("z is greater than x,y")
```


```python
if(y % x == 0 and x != 0): 
    print("y is divisible by x")
```

    y is divisible by x



```python
x, y, z = 2, 1, 4
```


```python
if( value := x > y or y < z):
    print(value)
```

    True



```python
if( value := x > y or y > z):
    print(value)
```

    True



```python
if(value := x < y or y < z):
    print(value)
```

    True



```python
if(value := x < y or y > z):
    print(value)

```


```python
x, y = 2, 1
```


```python
if(value := (x == 2) and not(y == 2)):
    print(value)

```

    True



```python

```


---
**Score: 15**