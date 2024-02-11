---
up: "[[Types]]"
tags:
  - type/type
created: 2024-02-11
cssclasses:
  - banner-image
displayname: Persons
---
> [!banner-image] ![[People1.png]]
## Collections
```dataview
list without id link(file.name, displayname) from "90 System" and !"90 System/Templates" where type = [[]]
```
## Instances
```dataview
table born, died, collections from !"90 System" where type = [[]]
```
