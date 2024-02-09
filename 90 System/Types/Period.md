---
up: "[[Types]]"
tags:
  - type/type
cssclasses:
  - cards
  - table-max
key: type/period
---
## Collections
```dataview
list from #type/collection 
where type = [[]]
```

## Instances
```dataview
table 
banner,
(dateformat(start,"yyyy") + "-" + dateformat(end,"yyyy")) as "Span" 

from #type/period and !"90 System"
sort start
```
