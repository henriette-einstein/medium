---
up: "[[50 Sources]]"
tags:
  - Type/Tagpage
created: 2024-02-29
key: Source/Article
aliases:
  - "#Source/Article"
---
# [[50 Sources]] > [[Articles]]
## Instances
```dataview
table author, url from !"90 System"
where econtains(tags, this.key)
sort file.name
```
