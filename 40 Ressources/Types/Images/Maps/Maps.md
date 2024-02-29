---
up: "[[Images]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Type/Image/Map
aliases:
  - "#Type/Image/Map"
---
# [[Images]]  > [[Maps]]
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
