---
up: "[[System]]"
type: "[[MOC Type]]"
created: 2024-02-06
---
```dataview
table without id link(file.name, displayname) as "Collection", link(type, type.displayname) as "Type" 
from #type/collection and !"90 System/Templates"
sort displayname
```
