---
title: Loop3
date: 2025-04-29
author: Your Name
cell_count: 15
score: 15
---

```python
#created at 20250124
```


```python
https://www.scientecheasy.com/2022/10/for-loop-in-python.html/
```


```python
num = int(input("Enter the limit: "))
```

    Enter the limit:  10



```python
even =0
```


```python
odd = 0
```


```python
for n in range(num):
    if n % 2 == 0:
        even = even + n
    else:
        odd = odd + n
```


```python
print("odd number total",odd)
```

    odd number total 25



```python
print("even number total",even)

```

    even number total 20



```python
num = int(input("Enter a number:"))
```

    Enter a number: 6



```python
fact = 1
```


```python
if num < 0:
    print("please enter a positive number bcz negative value we cant get")
elif num == 0:
    print("we cant calculate factorial for zero")
else:
    for i in range(1 , num + 1):
        fact = fact * i
        print("factorial of num:",num, "is:",fact)
```

    factorial of num: 6 is: 86400
    factorial of num: 6 is: 172800
    factorial of num: 6 is: 518400
    factorial of num: 6 is: 2073600
    factorial of num: 6 is: 10368000
    factorial of num: 6 is: 62208000



```python
nlist = [ 2, 4, 6, 8, 10]
```


```python
print("original order:",nlist)
```

    original order: [2, 4, 6, 8, 10]



```python
for x in nlist:
    print(x, end= ' ')
num = len(nlist) # Here, function len() returns the number of items in the container.
i = 0
j = -1
print('\nList of numbers in reverse order: ')
while i <= num - 1:
    print(nlist[j], end=' ')
    j -= 1
    i += 1

```

    2 4 6 8 10 
    List of numbers in reverse order: 
    10 8 6 4 2 


```python

```


---
**Score: 15**