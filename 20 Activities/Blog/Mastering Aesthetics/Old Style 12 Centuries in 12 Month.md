---
up: "[[Mastering Aesthetics in Obsidian]]"
type: "[[Note Type]]"
cssclasses:
  - embed-strict
---
> [!info]- Logistics
> ![[Logistics]]

> [!Example]- Sources to refer to
> ![[Sources]]

> [!Tip]- Eras
> ![[Eras]]

```dataview
table 
(start.year + "-" + end.year) as "Span" 
from #type/century and !"90 System"
where start.year < 2001
sort start
```