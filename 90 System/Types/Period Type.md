---
up: "[[Types]]"
tags:
  - type/type
key: type/period
created: 2024-02-11
displayname: Periods
---
## Collections
```dataview
list without id link(file.name, displayname) from "90 System" and !"90 System/Templates" where type = [[]]
```
## Instances
```dataview
table start, end, collections from !"90 System" where type = [[]]
```

## Instances
```dataview
table 
banner,
(dateformat(start,"yyyy") + "-" + dateformat(end,"yyyy")) as "Span" 

from #type/period and !"90 System"
sort start
```
