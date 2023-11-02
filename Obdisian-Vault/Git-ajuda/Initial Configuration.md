On git bash:
Using this video: [Git and GitHub for Beginners Tutorial - YouTube](https://www.youtube.com/watch?v=tRZGeaHPoaw&t=2428s)
# Setting user name
git config --global user.name "{Name here}"
## Example
```
$ git config --global user.name "Gustavo Assad Rocha" 
```

# Setting user email
git config --global user.email {email here}
## Example
```
$ git config --global user.email gassadrocha@gmail.com
```

# Getting Status
You need to go to the folder with the repository with:
- cd {path to the folder}
```
$ cd C:\ChoreMate
```
And then write 
```
git status
```

# Adding/removing a file to the list of tracked files
## Adding:
#### Specific file
```
$ git add {file name}
```
#### All files
```
$ git add .
```

## Removing
```
$ git rm --cached {file name}
```

# Ignoring files
Create a .gitignore file ....

# Commit
Means to take a picture of the situation of the software.
"-m" means  "message"
```
$ git commit -m "This is my first commit"
```


# Git diff
To see the differences that were made on the files
```
$ git diff 
```


# Place holders for files
1. Working files: files that you are working/editing right now
2. Staging: a place to hold files that you intend to commit. A in between place. 
3. Commit: when you are sure about the changes and make a register to the history of changes.

# Bypass staging
```
$ git commit -a -m "{message here}"
```

# See all commits
```
$ git log
```
## To see more detail:
```
$ git log -p
```
To exit: press q

