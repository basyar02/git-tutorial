# Git-tutorial
Git tutorial


## Pre-Requisite
### For Windows
1- Download Gitbash or any terminal :
- https://git-scm.com/downloads

2- Clone this repository :
```
git clone git@github.com:basyar02/git-tutorial.git
```

## Common command that will be used.
1- To create branch :
```
git checkout -b <branch_name>
```

2- To push branch :
```
git push -u origin <branch_name>
```

3- To pull branch :
```
git pull -r origin <branch_name>
```

4- To rebase your branch with master branch :
```
git rebase origin master
```

5- Check changes locally
```
git status
```

6- Add changes to the branch locally (need to be done before commit):
```
git add .
```

7- Commit your changes to the current branch (with message):
```
git commit -m "<any message"
```


** Note **
Don't make changes on `master` branch!!
