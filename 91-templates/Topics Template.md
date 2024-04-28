## Notes 
```dataview
table 
	dateformat(created, "dd MMM yyyy") as Created
where
	contains(topics,this.file.link) and
	!contains(file.name,"Template")
sort year desc
```
