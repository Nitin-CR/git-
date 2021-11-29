* A submodule is nested inside another parent repository
* You can modify, pull, push etc from any other repository.
* PS: A parent repository only stores the submodule's remote URL

To get the path and remote URL
```
cat .gitmodules
```

* We should create a folder to store the submodule.

```
git submodule add (url of the repository)

git clone --recurse-submodule(url) #In case the sub module contains a sub module

```
to commit
```
git commit
```

PS: when cloning the repositories which has submodules, At first we wont get those submodules, instead we only get empty folders.
