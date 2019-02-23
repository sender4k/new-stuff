# new-stuff

Git standard working stuff:

clone new repo:
```
git clone https://repo-link
```

add all local changes to staging area:
```
git add -A
```

commit staged changes:
```
git commit -m "What my changes do"
```

add changes to staging area and commit at the same time:
```
git commit -am "What my changes do"
```

create new branch:
```
git checkout -b my-new-branch-name
```

push new branch to remote repository (first time):
```
git push -u origin my-new-branch-name
```

list all local branches:

```
git branch
```

list all connected remote repositories:
```
git remote
```

Casual workflow:
```
git checkout master // if not already there
git pull // get latest changes from remote repo
git checkout -b new-feature // create new branch from master
// develop feature...
git status // job is done, check the list of changed files
git diff filename.ext // look at changes in a specific file
git add -A // add all changes to staging area
git status // optianal final look at changed files
git commit -m "Commit message" // describe commit changes
// first time push?
git push -u origin new-feature // sync current branch with remote branch
// not first time?
git push // just push new changes to remote branch

```