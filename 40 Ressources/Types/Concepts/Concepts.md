---
up: "[[Types]]"
tags:
  - Type/Tagpage
displayname: Concepts
created: 2024-02-13
aliases:
  - "#Type/Concept"
key: Type/Concept
---
# [[Concepts]]
## Subtags
```dataview
list from !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
list from !"90 System"
where econtains(tags, this.key)
sort file.name
```
