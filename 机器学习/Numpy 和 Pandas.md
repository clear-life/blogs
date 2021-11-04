# Numpy 和 Pandas

## Numpy

**算数运算**

对应元素都运算

```python
x = np.array([1, 2, 3])
y = np.array([2, 3, 4])
x + y
: array([3, 5, 7])

x / 2
: array([0.5, 1, 1.5])
```

**广播**

扩展数据

```python
x = np.array([[1, 2],
              [3, 4]])
y = np.array( [2, 3] )

x * y
: array([[2, 6],
         [6, 12]])
```

