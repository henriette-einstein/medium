---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: 2024-02-13
aliases:
  - "#Type/Person"
key: Type/Person
cssclasses:
  - banner-image
---

> [!banner-image] ![[People1.png]]
# [[Persons]]
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
table country, born, died from !"90 System"
where econtains(tags, this.key)
sort file.name
```
