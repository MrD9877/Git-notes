# Git-notes
All code SYNTAX to work with git 

# README SYNTAX
```
#A first-level heading
##A second-level heading
###A third-level heading **Give space between # and text for it to works**
```

Style	Syntax	Keyboard shortcut	Example	Output\
Bold	** ** or __ __	 Ctrl+B (Windows/Linux)	**This is bold text**\
Italic	* * or _ _     	  Ctrl+I (Windows/Linux)	_This text is italicized_\
Strikethrough	~ ~ ~ ~ (no space in ~ ~)~~This was mistaken text~~	\
Bold and nested italic	** ** and _ _**This text is _extremely_ important**\
All bold and italic	*** ***	None	***All this text is important***\
Subscript	<sub> </sub>	None	This is a <sub>subscript</sub>\
Superscript	<sup> </sup>	None	This is a <sup>superscript</sup> text\


# GIT
## GIT CLONE SYNTAX

**git**  clone <--link-->\
**git**  status \
**git**  add  <--file name-->\
**git**  commit -m *"msg"*  (its imortant to commit to push changes)\
**git**  push origin __main__(master{branch you want to push})\

## INIT GIT IN EXISTING PROJECT
**git**  init \
**git** remote add __origin__ <--link-->\
**git**  remote -v (to verify remote)\
**git**  branch (to verify branch)\
**git**  branch -m <--branch name-->  (to change branch name)\
**git**  add  <--file name-->\
**git**  commit -m *"msg"*  (its imortant to commit to push changes)\
**git**  push origin __main__(master{branch you want to push})\

## BRANCH COMMANDS
To check branch
```
git branch 
```
To rename branch
```
git branch -m main 
```
To navigate branch 
```
git checkout <--branch name--> 
```
To create and navigate branch 
```
git checkout -b <--branch name--> 
```
To delete and navigate branch 
```
git checkout -D <--branch name--> 
```
## MERGE CODE

### WAY 1
TO compare commits,branches,files and more
```
git diff <--branchname-->
```
To merge two branches
```
git merge <--branch name-->
```

### WAY 2

***CREATE A PULL REQUEST***

## PULL COMMAND
```
git pull origin <--branch name-->
```
## UNDO CHANGES
### CASE 1
**STAGED CHANGE**(add)\
For a specific file
```
git reset <--file name-->
```
For Whole project
```
git reset
```
### CASE 2
**COMMIT CHANGE**(FOR ONE COMMIT)\
```
git reset HEAD~1
```
### CASE 3
**COMMIT CHANGE**(FOR MANY COMMIT)\
```
git reset <--COMMMENT HASH-->
```
TO UNDO IN EDITOR
```
git reset --hard <--COMMMENT HASH-->
```








