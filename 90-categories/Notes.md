
```dataview
table 
	dateformat(created, "dd MMM yyyy") as Created
where
	contains(category,this.file.link) and
	!contains(file.name,"Template")
sort year desc
```