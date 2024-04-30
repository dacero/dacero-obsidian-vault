## Active projects and posts
```dataview
table 
	dateformat(created, "MMM yyyy") as Created,
	category as Category,
	status as Status
where
	(contains(category,[[Projects]]) or 
	contains(category,[[Posts]])) and
	!contains(file.name,"Template") and
	contains(status, "🟢")
sort year desc
```
