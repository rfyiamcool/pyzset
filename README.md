# pyzset

```
from zset import SortedSet

ss = SortedSet()
ss["a"] = 100
ss["a"] = 200
ss["b"] = 300

ss.by_score[200:300]
```

code base on https://github.com/tailhook/sortedsets , optimize query performance, reduce space size, clear useless function...
