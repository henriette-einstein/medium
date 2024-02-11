---
up: "[[Types]]"
tags:
  - type/type
created: "{{date}}"
displayname:
---
## Collections
```dataview
list without id link(file.name, displayname) from "90 System" and !"90 System/Templates" where type = [[]]
```
## Instances
```dataview
table collections from !"90 System" where type = [[]]
```
