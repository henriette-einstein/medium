---
up: "[[MOCs]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Type/MOC/History
aliases:
  - "#Type/MOC/History"
---
# [[MOCs]] > [[Historical MOCs]]
## Subtags
```dataview
list without id link(file.name, displayname) from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
