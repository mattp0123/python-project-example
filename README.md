# python-project-example

This is a flat-layout python project created with PDM. `setuptools` will discover
local packages automatically (with [default exclude](https://setuptools.pypa.io/en/latest/userguide/package_discovery.html#flat-layout)).

## Import module from local package

```python
from lib.utils import my_func

my_func()
```
