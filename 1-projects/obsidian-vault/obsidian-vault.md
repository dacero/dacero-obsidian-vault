---
category:
  - "[[Projects]]"
status: 🟢
created: 2024-04-28
---
## 📫 Inbox
```dataview
TASK
WHERE !completed AND
 contains(tags, "#inbox") AND
 contains(outlinks, this.file.link)
  ```
 
## 🎯 Target
- Create a reusable template for an obsidian vault that others can use.
- Document the methodology supported by this vault.
- Publish the templated as a publi repo.

## 📦 Project Box

- Heavily inspired by kepano's work: https://stephango.com/vault

## ✅ Next Up…


## 🌱 Journal

### 2024-05-19@12:27 -  Anchor Categories
- **Anchor categories** are those special categories that you come back recurrently.
- These are my anchor categories:
	- [[Projects]]
	- [[People]]
	- Areas of responsibility that have a dedicated recurrent governance (e.g. finance)
	- Daily Notes (I know that I will open one on a daily basis)
- You must be able to **send a message** to an anchor category from anywhere in your vault (e.g. you're in a meeting, a new information comes up that's relevant to a project, you send a message to the project.)
- Because you know that you will open the anchor category in the future, a message sent to them will be read.
- When you can trust that such message will be read, it really stays out of your mind.
- **Sending a message** to an Anchor Category is done by:
	- Creating a task
	- With the #inbox tag
	- And the reference to the Anchor point in it.
- **Reading a message** is done through the **Inbox**:
	- A special query on top of the page based on the [[Inbox Query Template]]

### 2024-04-28@19:05 - Creating the repo in GitHub

- [x] Create the repo in GitHub
	- Already created at 19:11 

### 2024-04-28@12:07 - Creating a frame for the notes use case

- [x] Create a skeleton for the notes section
	- This is going to need some thinking
	- Well, it's now 18:42, after some hiatus I've finished with a minimal setup.
	- Just two notes categories:
		- [[Notes]] - will include evergreen notes.
		- [[Captures]] - will include any other note that stems from a source.

### 2024-04-28@11:29 - Finishing project methodology

- 11:29 Complete the description of the `sessions`.
- [x] Finish describing the process to manage projects in [[Readme]].
- [x] Create a [[Projects]] page showing all existing projects
	- It requires the `Dataview` plugin… installed.
	- Had to learn to format the date with `dateformat()`, good result:
	- ![[projects screenshot.png]]
	- The status looks better with an emoji. I now need to create a list of potential status here.
	- Now I need to understand where to leave all the `categories`. Kepano uses a dedicated folder for that. Let's apply the same logic. Should it be the `1-categories` or the `7-categories`?
		- I think it's more the 7, in the sense that it's part of the meta structure of the vault.
		- Now I'm thinking that I might have to create 90, 91, 92 as META folders. Yes, updated to have the 9X as META folders.
- [x] Create a list of emojis with the potential project status

### 2024-04-28@08:50 - Project creation

- Project was created
- [x] Include kepano's url in the box
- [x] Fix the date in the project template.