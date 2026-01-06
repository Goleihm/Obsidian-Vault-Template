---
genre:
  - media
type:
  - list
tags:
  - index
---
### Media
#### Literature
###### Author
```dataview
TABLE publish-year, author 
FROM #Literature  
SORT publish-year asc
```
###### Latest
```dataview
TABLE publish-year, author 
FROM #Literature  
SORT file.ctime desc
```
#### Videos
```dataview
TABLE type, genre
FROM #video  
SORT type desc
Sort genre desc
```
#### Art
```dataview
TABLE publish-year
FROM #artist
SORT publish-year Desc
```
#### Audio
```dataview
TABLE publish-year
FROM #Audio
SORT publish-year Desc
```
#### Misc Download
```dataview
TABLE type, genre
FROM #MiscMedia 
SORT type desc
Sort genre desc
```
##### Statistics
```dataview
TABLE
FROM #_s
```

### College Courses
#### All Courses
```dataview
TABLE semester
FROM #College_Course
SORT semester desc
```