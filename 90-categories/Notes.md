
```dataview
table 
	dateformat(created, "MMM yyyy") as Created
where
	contains(category,this.file.link) and
	!contains(file.name,"Template")
sort year desc
```