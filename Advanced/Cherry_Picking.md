* Integrating one branch into another.
* Integrating specific comments.

For eg : we want a specific commit to be on the feature branch instead of the master branch

First we switch to feature branch

```
git checkout feature/name
```
```
git cherry-pick (Hash of the commit)
```
 To clear it from the master branch
 
 ```
 git checkout master
 git reset --hard HEAD~1`
 ```
