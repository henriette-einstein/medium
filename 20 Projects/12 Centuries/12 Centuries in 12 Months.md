---
up: "[[Projects]]"
tags:
  - type/project
created: 2024-01-30
cssclasses:
  - banner-image
  - embed-strict
  - img-float
  - cards
  - cards-cols-4
---
>[!banner-image] ![[Office12.png|py-60]]

 > [!img-float|pr-30] ![[Hourglass8.png]]
 > ![[Topics]]


```dataview
table 
banner,
(dateformat(start,"yyyy") + "-" + dateformat(end,"yyyy")) as "Span" 
from #type/century and !"90 System"
where start.year < 2001
sort start
```

