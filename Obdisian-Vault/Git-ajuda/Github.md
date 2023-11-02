
# Pushing existing repository for the first time in command line
git remote add origin {url of your repository} 
```git
$ git remote add origin https://github.com/yalmeidarj/Household-Chores-Management.git
```
If the repository already exists and the connection already has been established, you will get this message: 

```git
error: remote origin already exists.
```

# Pushing to Github 
You first need to set the target branch to main:
git branch -M main
```
$ git branch -M main
```

If you just created the repository don't forget to do a first commit:
```
$ git commit -m "initial commit"
```

Then pushing:
git push -u origin main
```
$ git push -u origin main
```

# How to know the branches on Github
 git branch -r
```
$ git branch -r
```

# How to look see more information on the remote repository
git ls-remote

# How to pull repository
git pull