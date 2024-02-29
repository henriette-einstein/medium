---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Type/Timeline
aliases:
  - "#Type/Timeline"
---
# [[Timelines]]
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
