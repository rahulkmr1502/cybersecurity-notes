# NAVIGATION

## 1. The Root Directory
- The staring point for the file system is the **root folder**
- We call it the root but its actua directory name is **"/" (a single slash)**
- Confusingly there is a sub-directory named "root". These are not the same!

## 2. The Home Directory
- ***/home*** contains a home folder for each user on the system
- For example, my home folder is located at ***/home/rahul***

### Just Remember
/ means root <br>
~ means home(current user)

## 3. pwd: Print Working Directory
- "Where am I?" command
- Prints the path of your current working directory starting form the root **/**
- Example: on my desktop, ***/home/rahul/Desktop***

## 4. ls: List Contents
- List the content of a directory.
- With no options or arguments → current directory
- We can list a specific directory: ls path
- Example: ***ls /bin*** → list contents of ***/bin***

## 5. ls Options
- ls has many options. Two most common ones:
- -l(lowercase L): Long list format. shows lots of info(permission, owner, size, data, etc)
- -a: shows all files, including hidden files(thsoe starting with **.**)
- We can use combine options!<br>
  Example: ls -la <br>
  #### My favorite one is "ls -alps"
