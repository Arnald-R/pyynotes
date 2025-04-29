---
title: Break1
date: 2025-04-29
author: Your Name
cell_count: 7
score: 5
---

```python
# created at 20250125
```


```python
https://www.scientecheasy.com/2022/11/break-statement-in-python.html/
```


```python
for i in range ( 1 , 4):
    for y in 0,1,2,3,4:
        if (i == 2) and (y == 2):
            break
        print( i , y)
```

    1 0
    1 1
    1 2
    1 3
    1 4
    2 0
    2 1
    3 0
    3 1
    3 2
    3 3
    3 4



```python
num = int(input("enter the number to check the number in the list:"))
```

    enter the number to check the number in the list: 20



```python
list1 = [12,13,14,18,19]
for i in list1:
    if i == num:
        print("the number in the list")
        break    
else:
    print("number not in the goiven list")
```

    number not in the goiven list



```python

```


```python

```


---
**Score: 5**