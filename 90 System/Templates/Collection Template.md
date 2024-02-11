---
up: "[[Collections]]"
created: "{{date}}"
type: 
displayname:
---
## Instances

```dataview
table from !"90 System" 
where type = this.type
and contains(collections,[[]])
```
