---
tags:
  - type/moc
cssclasses:
  - cards
  - table-max
  - cards-cols-4
---
```dataview
table 
banner,
(dateformat(start,"yyyy") + "-" + dateformat(end,"yyyy")) as "Span" 

from #type/century and !"90 System"
```