# tzf-rs' Python binding.

It's probably the fastest Python package to convert longitude/latitude to timezone name.
See <https://ringsaturn.github.io/tz-benchmark/> for more performance data.

NOTE:

1. This package use a simplified polygon data and not so accurate around borders.
2. Rust use lazzy init, so first calling will be a little slow.
3. Use about 40MB memory

```bash
pip install tzf-rs-py
```

```python
from tzfrspy import get_tz

print(get_tz(116.3883, 39.9289))
```
