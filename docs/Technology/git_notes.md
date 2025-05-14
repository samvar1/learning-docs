# Git Command Shortcuts

## Common Git Command Reminders

***

Initialized a new repo for the current folder
``` git
git init
```

Clone a remote repository
``` git
git clone <remoteURL/>
```

Stage files for commit

Adds all the files to the stages

``` git
git add .
```

Commit the files with a message

Creates a version of your repo for point in time commit prior to staging

``` git
git commit -m "adding new files" 
```

Adding a remote repo

Publishing your code to github

``` git
git remote add <remotename> <remoteURL>
```

Creating a new local branch

``` git
git checkout -b <Name of Branch>

OR 

git switch -c <Name of Branch>
```

To switch from different branches 

``` git
git checkout <Name of Branch>

OR 

git switch <Name of Branch>
```

Fetch remote changes

Git fetch tells git to go to the default remote repo and donwload all the changes to the local repo 

``` git
git fetch <remoteName>
```

Git interactive rebase allows you to reaarange, eliminate, and much more

``` git
git rebase -i <remoteOrLocalBranchNameorCommitHash>
```

Git reset hard if you want to start from a clean slate. Gives you a new chance to throw anything not committed away. 

``` git
git reset --hard
```

If you want to stash your changes and then move to another branch without losing your work 

``` git
git stash <stashes uncommited changes>
git stash pop <retrieves the changes you stashed last>
git stash drop <drops the changes from your stashed list>
```

rename a branch if you misspelled or need to update the name

``` git
git branch -m <OldBranchName> <NewBranchName>
git push <remoteName> :<oldBranchName> <NewBranchName>
```

Show a commit log 
``` git
git log
```

Create a graph from all of the commit logs

``` git
git log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
```
