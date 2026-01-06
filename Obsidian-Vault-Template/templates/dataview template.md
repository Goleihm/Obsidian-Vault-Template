---
genre:
type:
  - list
tags:
  - index
---
###### All
```dataview
TABLE file.ctime as "Created"
FROM #<%tp.file.title%>
SORT file.ctime desc
```

- Subsection
	copy/paste dataview and add a tag to 'FROM' for more specific results. Place under different header than 'All' so as to keep organized / separate from 'All'