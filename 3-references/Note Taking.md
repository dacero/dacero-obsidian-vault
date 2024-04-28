## Notes 
```dataview
table 
	category as Category,
	dateformat(created, "dd MMM yyyy") as Created
where
	contains(topics,this.file.link) and
	!contains(file.name,"Template")
sort year desc
```
