---
up: "[[Types]]"
tags:
  - type/type
created: 2024-02-02
key: type/person
---
## Collections
```dataview
list from #type/collection 
where type = [[]]
```

## Instances

```dataview
table country, born, died 
from #type/person and !"90 System"
sort born
```
