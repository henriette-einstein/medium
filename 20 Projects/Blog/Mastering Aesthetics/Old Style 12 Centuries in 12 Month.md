---
up: "[[Mastering Aesthetics in Obsidian]]"
cssclasses:
  - embed-strict
tags:
  - Type/Note
---
> [!info]- Logistics
> ![[Logistics]]

> [!Example]- Sources to refer to
> ![[20 Projects/12 Centuries/Sources]]

> [!Tip]- Eras
> ![[Eras]]

```dataview
table 
(start.year + "-" + end.year) as "Span" 
from #type/century and !"90 System"
where start.year < 2001
sort start
```