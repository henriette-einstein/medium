---
up: "[[Types]]"
tags:
  - type/type
created: 2024-02-06
key: type/event
---
## Collections
```dataview
list from #type/collection 
where type = [[]]
```
## Instances

```dataview
table collections, start, end from #type/event and !"90 System"
sort file.name
```
