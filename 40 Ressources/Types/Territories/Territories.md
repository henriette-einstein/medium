---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: 2024-02-13
aliases:
  - "#Type/Territory"
cssclasses:
  - banner-image
key: Type/Territory
---
> [!banner-image] ![[Globe1.png]]

# [[Types]] > [[Territories]]
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
table from !"90 System"
where econtains(tags, this.key)
sort file.name
```
