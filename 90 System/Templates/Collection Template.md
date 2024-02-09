---
up: "[[Collections]]"
created: "{{date}}"
type:
---
## Instances

```dataview
table from !"90 System" 
where contains(tags, this.type.key)
and contains(collections,[[]])
```
