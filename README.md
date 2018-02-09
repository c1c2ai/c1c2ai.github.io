### 1. git config

> This command is used to set/unset the global options for the git on you local system. When you install git a file called .gitconfig is generated which stores all the global options. The above command helps to alter and play with the .gitconfig file. It also has various options which can be checked using:**git help config**

　

```

e.g. 1) git config  --global user.name "Chetan Choudhary"

e.g. 2) git config --get-all

```

　

### 2. git init

> Create an empty Git repository or reinitialize an existing one. This command is used for initializing  git for folder and its subfolders so that the folder with subfolders can be tracked for changes and become  a part of git cycle.

　

```

e.g. 1) git init

e.g. 2) git init ~/Desktop/FirstGitProject

```

　

### 3. git push

> This command is used to push the changes commited to a remote repository.

```

e.g. 1) git push origin master

e.g. 2) git push --all

```

### 4. git pull

> This command is used to pull the changes from a remote repository to local repository. All new changes in the remote repository are merged with the working local copy and a conflict might occur in some cases.

```

e.g. 1) git pull <remote repository>

e.g. 2) git pull --verbose <remote repository>

```

### 5. git clone

>Clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository, and creates and checks out an initial branch that is forked from the cloned repositoryâ€™s currently active branch..

```

e.g. 1) git clone <remote repository>

e.g. 2) git clone --verbose <remote repository>

```

### 6. git status

>Shows working tree structure. Shows which files are modified, new created.

Gives user the details which will help the user understand what to add and what to commit.

```

e.g. 1) git status 

e.g. 2) git status -s

```

### 7. git commit

>This command commits the added files to the repository with a log message

```

e.g. 1) git commit

e.g. 2) git commit -am "added config file"

```

　

　

### 8. git reset

>The git reset command is a complex and versatile tool for undoing changes.This command resets the HEAD and MASTER to the specified commit

```

e.g. 1) git reset

e.g. 2) git reset --hard 

```

　

　

### 9. git checkout

>This command is used to switch over the branches in the repository

```

e.g. 1) git checkout <branchname>

e.g. 2) git checkout -b <branchname>

```

### 10. git branch

>This command is used to see all the branches available in the repository. It can also be used to create a new branch if a branch name is passed as a parameter to the command

```

e.g. 1) git branch

e.g. 2) git branch samplebranch 

```

　

### 11. git merge

>This command is used to merge the changes from branch which is ahead of the branch on which it is executed. This command helps in syncing master copy with other branches. The user needs to be on a branch which is behind which can be done using the checkout command

```

e.g. 1) git merge <ahead branch>

e.g. 2) git merge --no-ff <branch>

```

　

### 12. git mv

>Move or rename a file, a directory, or a symlink

```

e.g. 1) git mv oldname newname

e.g. 2) git mv -f oldname newname 

```

　

### 13. git rm

> Remove files from the working tree and from the index

```

e.g. 1) git rm <files>

e.g. 2) git rm -f <files> 

```

　

### 14. git add

>This command is used to add the modified files / new files to the staging tree which prepares them for later adding to the commit tree

```

e.g. 1) git add .

e.g. 2) git add -f -v  all 

```

　

### 15. git diff

>Show changes between commits, commit and working tree, etc

```

e.g. 1) git diff HEAD [filename]

e.g. 2) git diff [filename]

```

　

　

　
