---
title: Sys1
date: 2025-04-21
author: Your Name
cell_count: 7
score: 5
---

```python
#created at 20250204
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/pythons-sys-module
```


```python
#command line arguments
```


```python
import sys

if __name__ == "__main__":
    print("Command-line arguments:")
    for arg in sys.argv:
        print(arg)
```

    Command-line arguments:
    /home/arnald/miniconda3/envs/py312/lib/python3.12/site-packages/ipykernel_launcher.py
    -f
    /home/arnald/.local/share/jupyter/runtime/kernel-840e4cdf-8000-4dd7-bf49-da657e8e245f.json



```python
import sys

def main():
    print("This is an example of sys.exit()")
    sys.exit(0)

if __name__ == "__main__":
    main()
```

    This is an example of sys.exit()



    An exception has occurred, use %tb to see the full traceback.


    SystemExit: 0



    /home/arnald/miniconda3/envs/py312/lib/python3.12/site-packages/IPython/core/interactiveshell.py:3585: UserWarning: To exit: use 'exit', 'quit', or Ctrl-D.
      warn("To exit: use 'exit', 'quit', or Ctrl-D.", stacklevel=1)



```python
import sys

with open('output.txt', 'w') as f:
    sys.stdout = f
    print("This will be written to output.txt")
    
sys.stdout = sys.__stdout__  # Resetting stdout
```


```python

```


---
**Score: 5**