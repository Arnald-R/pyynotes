---
title: File-Handling
date: 2025-04-29
author: Your Name
cell_count: 13
score: 10
---

```python
#day 9
```


```python
with open("sample.txt",'w') as file:
    file.write("Hi this the 9 day\n Welcome to the file")
```


```python
with open("sample.txt",'r') as file:
    content = file.read()
    print(content)
```

    Hi this the 9 day
     Welcome to the file



```python
#json
import json
```


```python
data = {
    "name" : "Arnald",
    "age": 23,
    "locat": "poy"
}
```


```python
with open("data.json", "w") as file:
    json.dump(data, file, indent=4)
    
```


```python
with open("data.json", "r") as file:
    loaded_data = json.load(file)
    print(loaded_data)
```

    {'name': 'Arnald', 'age': 23, 'locat': 'poy'}



```python
#csv
import csv
```


```python
rows = [
    ["Name","Age","Place"],
    ["Arnald",23,"Pollachi"],
    ["Ambu",25,"Cbe"]
]
```


```python
with open("data.csv", "w", newline="") as file:
    writing = csv.writer(file)
    writing.writerows(rows)
```


```python
with open("data.csv", "r")as file:
    reader = csv.reader(file)
    for row in reader:
        print(row)
```

    ['Name', 'Age', 'Place']
    ['Arnald', '23', 'Pollachi']
    ['Ambu', '25', 'Cbe']



```python

```


```python

```


---
**Score: 10**