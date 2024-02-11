---
up: "[[Collections]]"
type: "[[MOC Type]]"
created: 2024-02-11
displayname: Sections
---
## Instances

```dataview
table from !"90 System" 
where type = this.type
and contains(collections,[[]])
```
