---
title: Ex-7
date: 2025-04-26
author: Your Name
cell_count: 25
score: 25
---

```python
#created at 20250423
```


```python
#Basic Lineplot
```


```python
import matplotlib.pyplot as plt
import numpy as np
```


```python
plt.figure(figsize=(10, 6))
```




    <Figure size 1000x600 with 0 Axes>




    <Figure size 1000x600 with 0 Axes>



```python
x = np.linspace(0, 10, 100)
```


```python
y = np.sin(x)
```


```python
plt.plot(x, y, label='sin(x)')
```




    [<matplotlib.lines.Line2D at 0x7fea11d6e2a0>]




    
![png](/pyynotes/images/ex-7_6_1.png)
    



```python
plt.title('Basic Line Plot')
```




    Text(0.5, 1.0, 'Basic Line Plot')




    
![png](/pyynotes/images/ex-7_7_1.png)
    



```python
plt.xlabel('x')
```




    Text(0.5, 0, 'x')




    
![png](/pyynotes/images/ex-7_8_1.png)
    



```python
plt.ylabel('y')
```




    Text(0, 0.5, 'y')




    
![png](/pyynotes/images/ex-7_9_1.png)
    



```python
plt.legend()
```

    /tmp/ipykernel_63496/4061938096.py:1: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
      plt.legend()





    <matplotlib.legend.Legend at 0x7fea1172fbc0>




    
![png](/pyynotes/images/ex-7_10_2.png)
    



```python
plt.savefig('line_plots.png')
```


    <Figure size 640x480 with 0 Axes>



```python
plt.close()
```


```python
plt.figure(figsize=(10, 6))

```




    <Figure size 1000x600 with 0 Axes>




    <Figure size 1000x600 with 0 Axes>



```python
plt.subplot(1, 2, 1)

```




    <Axes: >




    
![png](/pyynotes/images/ex-7_14_1.png)
    



```python
plt.plot(x, np.sin(x), 'b-', label='sin(x)')
```




    [<matplotlib.lines.Line2D at 0x7fea11546630>]




    
![png](/pyynotes/images/ex-7_15_1.png)
    



```python
plt.title('sine')
```




    Text(0.5, 1.0, 'sine')




    
![png](/pyynotes/images/ex-7_16_1.png)
    



```python
plt.legend()
```

    /tmp/ipykernel_63496/4061938096.py:1: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
      plt.legend()





    <matplotlib.legend.Legend at 0x7fea11633230>




    
![png](/pyynotes/images/ex-7_17_2.png)
    



```python
plt.subplot(1, 2, 2)
```




    <Axes: >




    
![png](/pyynotes/images/ex-7_18_1.png)
    



```python
plt.plot(x, np.cos(x), '-r', label='cos(x)')
```




    [<matplotlib.lines.Line2D at 0x7fea1156c2c0>]




    
![png](/pyynotes/images/ex-7_19_1.png)
    



```python
plt.title('cosine')
```




    Text(0.5, 1.0, 'cosine')




    
![png](/pyynotes/images/ex-7_20_1.png)
    



```python
plt.legend()
```

    /tmp/ipykernel_63496/4061938096.py:1: UserWarning: No artists with labels found to put in legend.  Note that artists whose label start with an underscore are ignored when legend() is called with no argument.
      plt.legend()





    <matplotlib.legend.Legend at 0x7fea10722480>




    
![png](/pyynotes/images/ex-7_21_2.png)
    



```python
plt.savefig('multiplots.png')
```


    <Figure size 640x480 with 0 Axes>



```python
plt.close()
```


```python

```


---
**Score: 25**