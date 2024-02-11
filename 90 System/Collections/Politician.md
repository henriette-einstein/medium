---
up: "[[Collections]]"
tags:
  - type/collection
created: 2024-02-06
type: "[[Person Type]]"
displayname: Politicians
---
## Instances

```dataview
table country, born, died from !"90 System" 
where type = this.type
and contains(collections,[[]])
```
