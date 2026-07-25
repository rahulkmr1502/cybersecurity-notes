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
- Example: on my desktop, ***$ pwd*** will show ***/home/rahul/Desktop***

## 4. ls: List Contents
- List the content of a directory.
- With no options or arguments → current directory
- We can list a specific directory: ls path
- Example: ***$ ls /bin*** → list contents of ***/bin***

## 5. ls Options
- ls has many options. Two most common ones:
- -l(lowercase L): Long list format. shows lots of info(permission, owner, size, data, etc)
- -a: shows all files, including hidden files(thsoe starting with **.**)
- We can use combine options!<br>
  Example: ***$ ls -la*** 
  
## 6. cd: Changing Directory
  - Used to change (or "move") into another directory.
  - ***cd <directory>*** change current directory
  - Example: ***cd chickens*** → move into chicken directory(if it exists)
  - Exmaple: ***cd /home/rahul*** → go to my home directory

## 7. cd.. : backing up
- In Unix-like systems:<br>
**.** means current directory <br>
**..** means parent directory (one level up)
- Use ***cd..*** to move up one level.

## 8. Relative Paths
- Paths that specify a directory/file relative to the current directory
- Example: if current directory is ***/home/rahul*** and we want to ***cd*** into animals:<br>
    ***$ cd annimals*** works here
- But ***cd animals*** does not work if we are in another directory(eg, ***/bin***)
- From ***/bin***, the relative path is <br>
***../home/rahul/animals***

## 9. Absolute Paths
- Absolute paths starts from the root directory(they start with **/**)
- The full location of a file/directory, no matter where we are in the system
- Example: ***/home/rahul/animals/dogs/chickens***
- Works from any directory
