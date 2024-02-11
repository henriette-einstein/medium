---
up: "[[Collections]]"
created: 2024-02-11
type: "[[MOC Type]]"
displayname: Indices
---
## Instances

```dataview
table file.folder as "Folder" from !"90 System" 
where type = this.type
and contains(collections,[[]])
```
