---
title: Clean Python but typos
published: true
---
I have read Clean Python by Sunil Kapil.  
I read about 30 pages and noticed some typos in the example code.  
Perhaps this book is not for beginners.
It is difficult to understand the topic when you are not sure that the examples are written correctly..
* * *

For example.  
This code should return a list of True-values. But here`s typos.
```Python
data = [1, "A", 0, False, True]
filtered_data = [item for item in filter if item]
```

Or.  
This code should return a minimum value from the list.
```python
data = [[7], [3], [0], [8], [1], [4]]
def min_val(data):
"""Find minimum value from the data list."""
    return min(data, key=lambda x:len(x))
```
Not this time..
* * *
etc
