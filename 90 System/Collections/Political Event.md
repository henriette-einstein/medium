---
up: "[[Collections]]"
tags:
  - type/collection
created: 2024-02-06
type: "[[Event Type]]"
---
## Instances

```dataview
table start, end from !"90 System" 
where type = this.type
and contains(collections,[[]])
```
