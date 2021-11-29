 It is a tool for optimizing and cleaning up your commit history.
 
* It changes a commit's message
* Deletes, combines and reorder's commits 
* Used to edit/split an existing commit into multiple new ones

```
git rebase -i HEAD~3
```

# Work Flow

* Determine the base commit
* We can choose the operation needed to be performed.

```
# p, pick 
# r, reword 
# e, edit 
# f, fixup 
# x, exec 
# d, drop 

# git rebase --abort  # It is like force-stop

```
Deleting a commit

The syntax is 'Drop' followed by the commit
