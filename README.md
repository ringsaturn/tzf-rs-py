# tzf-rs' Python binding.

```bash
pip install tzf-rs-py
```

NOTE: Rust use lazzy init, so first calling will be a little slow.

```python
from tzfrspy import get_tz

print(get_tz(116.3883, 39.9289))
```
