---
up: "[[Types]]"
tags:
  - type/type
created: 2024-02-09
banner: "![[Globe6.png]]"
---
![[Globe6.png]]
## Collections
```dataview
list from "90 System" where type = [[]] and up = [[Collections]]
```
## Instances
```dataview
table default(thumbnai,meta(type.banner).path) as "Thumbnail" from !"90 System" 
where type=[[]]
```



```dataview
table choice(thumbnail,regexreplace(default(thumbnail,""),"!\[.*\]","![img|150]"),"--") as "Thumbnail" from !"90 System" 
where type=[[]]
```

[[40 Ressources/Weblinks/Wikipedia/Carolingian Renaissance.md|Carolingian Renaissance]]
