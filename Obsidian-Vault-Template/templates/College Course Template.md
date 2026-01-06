---
genre:
type:
tags:
  - College_Course
semester: n/a
---
[Prof. Name](email) - [[|Syllabus]]
Class Number

Meet: Location
Office: Location
	Times: Office Hours

###### Literature
```dataview
TABLE file.ctime as "Created"
FROM #<%tp.file.title%> and #Literature
SORT file.ctime desc
```

###### Lecture
```dataview
TABLE file.ctime as "Created"
FROM #<%tp.file.title%> and #Lecture
SORT file.ctime desc
```
###### All
```dataview
TABLE file.ctime as "Created"
FROM #<%tp.file.title%>
SORT file.ctime desc
```