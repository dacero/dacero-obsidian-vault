
```dataview
table 
	dateformat(created, "MMM yyyy") as Created,
	status as Status
where
	contains(category,this.file.link) and
	!contains(file.name,"Template")
sort year desc
```
