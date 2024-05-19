---
category:
  - "[[Projects]]"
status: 🟢
created: {{date}}
next-action:
---

## 🎯 Target
*Tangible objective. Be specific. Set a date.*

## 📦 Project Box
*Useful stuff for the project*

## 🔗 Links to Project Notes
```dataview
table 
	category as Category,
	dateformat(created, "dd MMM yyyy") as Created
where
	contains(topics,this.file.link) and
	!contains(file.name,"Template")
sort year desc
```

## ✅ Next Up…
*Include here the next action.*

## 🌱 Journal
*Watch it grow*

### {{date}} {{time}} - Project creation
- Project was created
