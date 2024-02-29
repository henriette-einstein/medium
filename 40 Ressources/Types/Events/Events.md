---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: 2024-02-13
aliases:
  - "#Type/Event"
key: Type/Event
---
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
table start, end, tags from !"90 System"
where contains(tags, this.key)
sort file.name
```
