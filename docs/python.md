- https://docs.python.org/3/tutorial/classes.html#class-objects

```python
class Complex:
  '''Example'''
  def __init__(self, realpart, imagpart):
    self.r = realpart
    imagpart

x = Complex(3.0, -4.5)
x.r, x.i # == (3.0, -4.5)
```
