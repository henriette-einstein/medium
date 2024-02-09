---
up: "[[Home]]"
type: "[[MOC Type]]"
created: 2024-02-01
cssclasses:
  - banner-image
banner: "![[Postoffice5.png]]"
sortkey: 00 Inbox
---
>[!banner-image] ![[Postoffice5.png|py-70]]

# New Notes

```dataview
table striptime(file.ctime) as "Created", striptime(file.mtime) as "Last Modified" from "00 Inbox" and !"00 Inbox/Inbox"
```

# Notes to process

```dataview
table durationformat(date(today) - file.ctime,"d 'days' h 'hours' ") as "Age" from #status/todo and !"90 System"
sort file.ctime desc
```
