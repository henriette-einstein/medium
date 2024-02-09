---
up: "[[Activities]]"
type: "[[Project]]"
tags:
  - pinned
created: 2024-01-30
cssclasses:
  - banner-image
  - embed-strict
  - img-float
  - cards
  - cards-cols-6
banner: "![[Office12.png]]"
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
from !"90 System"
where contains(collections,[[Century]])
and start.year < 2001
sort start
```

