# Git Commands

```
git --version
```
It displays the git version if git is installed on the machine, if not installed - returns an error


```
git status
```
It shows the files which were created/modified on the local machine 


```
git clone
```
It creates a copy of the reposiotry in the local machine from github


```
git add (file_name)
```
It adds the mentioned file to commit


```
git add .
```
It adds all the files to commit


```
git commit -m "The message" -m "The description"
```
It adds a message and a description for the new commit

# Note : Adding commit doesn't mean that the file is added to the repository from the local machine. We have to use git push to achieve that.


```
git push (origin) (branch)
```
here origin is the file location and branch refers to the branch we want to push our file into.
git push works as well.


```
git pull
```
It gets the repo from github and adds it on the local machine
