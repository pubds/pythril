# pythril
Python data science tools for large data sets.

## Example

Extensions of the builtin `collections.counters` for counting faceted data.

```python
from pythril.counters import DictCounter

counter = Dictcounter(header=['x', 'y'])
counter.add(dict(x=1, y=2, z=3))
counter[(1, 2)] == 1  # True
```
