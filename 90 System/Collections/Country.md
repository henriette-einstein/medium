---
up: "[[Collections]]"
tags:
  - type/collection
created: 2024-02-08
type: "[[Territory Type]]"
displayname: Countries
---
```dataview
table from !"90 System" 
where type = this.type
and contains(collections,[[]])
```

