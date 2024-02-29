---
up: 
tags:
  - Type/Tagpage
created: "{{date}}"
key: 
aliases:
---
# [[{{title}}]]
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
