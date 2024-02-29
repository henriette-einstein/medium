---
up: "[[30 Atlas]]"
tags:
  - Type/MOC
created: 2024-02-09
---

```dataview
table "[["+replace(filter(tags, (x) => startswith(x,"Type")),"/"," ")+"]]" as "Type" from #pinned
```
