---
genre:
  - log
type: 
tags:
  - index
  - _cList
NoteDate: 2023-10-14T18:57:00
---
```dataview
TABLE file.ctime as "Created"
FROM #log 
SORT file.ctime desc
```
