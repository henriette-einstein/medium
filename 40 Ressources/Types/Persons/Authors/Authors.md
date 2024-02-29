---
up: "[[Persons]]"
tags:
  - Type/Tagpage
created: 2024-02-13
key: Type/Person/Author
aliases:
  - "#Type/Person/Author"
---
# [[Persons]] > [[Authors]]
## Instances
```dataview
table country, born, died from !"90 System"
where contains(tags, this.key)
sort file.name
```
