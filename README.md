# git-tutorial
## git personal training
- git create new branch
  `git checkout -b "branch-name"`
- list branch
  `git branch` or `git branch -a`
- change branch
  `git checkout "branch-name"`
- view existing remote
  `git remote -v`
-change the origin's remote URL
  `git remote set-url origin https://github.com/aminMuktar/socialsense.git`
- push to specific branch
   `git push --set-upstream origin "branch-name"`
- merge branch
    `git merge "branch" --no-ff`
- delete merged branch
    `git branch -d "branch-name"`
Git init
Initialize a new git repository 

Git add <file-name>
Add files to the staging area

Git reset
Undo changes to the local file. Restore to the last commit

✤ git diff
→ Displays the difference between files in two commits or between a commit and your current repository.

✤ git status

→ Used to check the state of the staging area, as well as the working directory.


✤ git log

→ Used to view the entire commit history.

✤ git commit -m "message"

→ Used to commit files (locally) on the repository.

✤ git branch

→ Used to list all the local branches on the machine.

✤ git branch <branch-name>

→ Used to create a new branch locally.

✤ git branch -d <branch-name>

→ Used to delete a branch.

✤ git branch -m <new-name>

→ Used to rename the current working branch.

✤ git merge <branch-name>

→ Merges the provided branch with the current working branch.

✤ git checkout <branch-name>

→ Used to switch from current branch to another one.

✤ git checkout -b <branch-name>

→ Creates a new branch and switches to the new one.


✤ git push <remote> <branch-name>

→ Used to save all commits to the remote repository.


✤ git pull <remote>

→ Used to pull down all the updates from the remote repository.

✤ git rm <file-name>

→ Used to remove a file from the working directory.

✤ git stash


## keeping historical copies
this copies lets you see what the project looks like before


### return the difference of two files

```
diff file1.py file2.py

```

### for graphical difference

```
vimdiff file1.py file2.py

```
→ Used to temporarily remove uncommitted changes.
