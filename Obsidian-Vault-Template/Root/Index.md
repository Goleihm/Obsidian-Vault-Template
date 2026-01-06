---
genre:
  - dataview
type:
  - list
tags:
  - "#index"
---
[[Introduction]]

#### All
```dataview
TABLE genre
FROM #index
SORT genre desc
```

##### Lists
```dataview
TABLE genre, type
FROM #list 
SORT type desc
SORT genre desc
```