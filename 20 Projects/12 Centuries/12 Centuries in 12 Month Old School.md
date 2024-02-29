---
cssclasses:
  - embed-strict
---

![[Details]]

```dataview
table (start.year + "-" + end.year) as "Span" 
from #type/century and !"90 System"
where start.year < 2001
sort start
```
