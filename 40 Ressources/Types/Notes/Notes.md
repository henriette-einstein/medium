---
up: "[[Types]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Type/Note
aliases:
  - "#Type/Note"
cssclasses:
  - banner-image
---
> [!banner-image] ![[Note1.webp]]
> 
# [[Types]] > [[Notes]]
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
table file.folder as "Folder" from !"90 System"
where econtains(tags, this.key)
sort file.name
```
