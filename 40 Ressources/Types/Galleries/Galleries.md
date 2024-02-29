---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Type/Gallery
aliases:
  - "#Type/Gallery"
cssclasses:
  - banner-image
---
> [!banner-image] ![[Livingroom3.png]]
> 
# [[Types]] > [[Galleries]]
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
