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
  - cards-cols-6
---
>[!banner-image] ![[Office12.png|py-60]]


 > [!img-float|pr-40] ![[Hourglass8.png]]
 > >[!info]- Logistics
 > >![[Logistics]]
 > 
>> [!Example]- Sources to Refer to
>> ![[Sources]] 
>
>> [!Tip]- Eras
>> ![[Eras]]

```dataview
table 
banner,
(start.year + "-" + end.year) as "Span" 
from #type/century and !"90 System"
where start.year < 2001
sort start
```

