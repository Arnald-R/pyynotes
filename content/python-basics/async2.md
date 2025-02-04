---
title: Async2
date: 2025-02-04
author: Your Name
cell_count: 8
score: 5
---

```python
#created at 20250201
```


```python
https://stevejoe1412.gitbook.io/ssn/python-subtopics/asynchronous-programming
```


```python
#Running multiple tasks concurrently
```


```python
import asyncio
```


```python
async def task1():
    print("task1 is started")
    await asyncio.sleep(2)
    print("task1 is completed")
```


```python
async def task2():
    print("task2 is started")
    await asyncio.sleep(1)
    print("task2 is completed")
```


```python
async def main():
    await asyncio.gather(task1, task2())

asyncio.run(main())
```


    ---------------------------------------------------------------------------

    RuntimeError                              Traceback (most recent call last)

    Cell In[6], line 4
          1 async def main():
          2     await asyncio.gather(task1, task2())
    ----> 4 asyncio.run(main())


    File ~/miniconda3/envs/py312/lib/python3.12/asyncio/runners.py:190, in run(main, debug, loop_factory)
        161 """Execute the coroutine and return the result.
        162 
        163 This function runs the passed coroutine, taking care of
       (...)
        186     asyncio.run(main())
        187 """
        188 if events._get_running_loop() is not None:
        189     # fail fast with short traceback
    --> 190     raise RuntimeError(
        191         "asyncio.run() cannot be called from a running event loop")
        193 with Runner(debug=debug, loop_factory=loop_factory) as runner:
        194     return runner.run(main)


    RuntimeError: asyncio.run() cannot be called from a running event loop



```python

```


---
**Score: 5**