---
up: "[[Timeframes]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Type/Timeframe/Era
aliases:
  - "#Type/Timeframe/Era"
---
# [[Timeframes]] > [[Eras]]
## Subtags
```dataview
list from #Type/Tagpage and !"90 System/Templates" 
where up = [[]]
sort file.name
```
## Instances
```dataview
table start, end from !"90 System"
where econtains(tags, this.key)
sort start
```
