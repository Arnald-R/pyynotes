---
title: Sys3
date: 2025-02-04
author: Your Name
cell_count: 6
score: 5
---

```python
#created at 20250204
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/pythons-sys-module
```


```python
import sys

print(f"Current recursion limit: {sys.getrecursionlimit()}")
sys.setrecursionlimit(2000)
print(f"Updated recursion limit: {sys.getrecursionlimit()}")
```

    Current recursion limit: 3000
    Updated recursion limit: 2000



```python
import sys

print("Please enter your name:")
name = sys.stdin.readline().strip()
print(f"Hello, {name}!")
```

    Please enter your name:
    Hello, !



```python
import sys

print("Something went wrong.")
sys.exit(1)  # Exit with error code 1
```

    Something went wrong.



    An exception has occurred, use %tb to see the full traceback.


    SystemExit: 1



    /home/arnald/miniconda3/envs/py312/lib/python3.12/site-packages/IPython/core/interactiveshell.py:3585: UserWarning: To exit: use 'exit', 'quit', or Ctrl-D.
      warn("To exit: use 'exit', 'quit', or Ctrl-D.", stacklevel=1)



```python

```


---
**Score: 5**