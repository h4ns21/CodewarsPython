# First method

```python
def find_smallest_int(arr):
    m = arr[0]
    for i in range(0, len(arr)):
        if(arr[i] < m):    
            m = arr[i]
    return m
```

# Second method

```python
def findSmallestInt(arr):
    return min(arr)
```
