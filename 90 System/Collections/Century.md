---
up: "[[Collections]]"
tags:
  - type/collection
created: 2024-02-07
type: "[[Period]]"
cssclasses:
  - cards
---
```dataview
table 
banner,
(dateformat(start,"yyyy") + "-" + dateformat(end,"yyyy")) as "Span" 
from !"90 System" 
where type = this.type
and contains(collections,[[]])
sort start
```
