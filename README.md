<h1 align="center"> Git Commands </h1>


***A list of commonly used Git commands***

<br>

<p> 

<img src="https://komarev.com/ghpvc/?username=Git-Commands-Github-Guide&label=Repo%20views&color=0e75b6&style=plastic?" alt="ahmedbadawi" height=25px, width=160px/> 

</p>

<br>

## Sources to learn Git :

- [What is GitHub?](https://youtu.be/pBy1zgt0XPc?si=BUJUk0q9wEVDROEX)

- [Ghareeb Elshaikh](https://youtu.be/fDkR0TDR9dI?si=HWaXAxboaJJzrcGg)

- [Git and GitHub From ==> بالعربي Big Data](https://youtu.be/Q6G-J54vgKc?si=j2sBM2RzbXEs_rbK)

- [Elzero Web School ==>   Git و Github playlist](https://youtube.com/playlist?list=PLDoPjvoNmBAw4eOj58MZPakHjaO3frVMF&si=8RrFWhswwkhCZ1qy)

- [Upload Flutter Project to GitHub from VS Code](https://youtu.be/PiweMDoWhqA?si=zJ35I7EIA1OiRxu2)

- [How to Upload Flutter Project on Github | Flutter Github Guide](https://youtu.be/DsUwTmSyfYE?si=ByqJiw7x1wcG8G99)


* ## [To Download Git](https://git-scm.com/downloads)

<hr>

* ## The Commands : 

### SETUP

| Command | Description |
| ------- | ----------- |
| `git config --global user.name “[firstname lastname]”` | set a name that is identifiable for credit when review version history |
| `git config --global user.email “[valid-email]”` | set an email address that will be associated with each history marker |
| `git config --global color.ui auto` | set automatic command line coloring for Git for easy reviewing |


### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### STAGE & SNAPSHOT

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file]` | Add a file to the staging area |
| `git add -A` or `git add .`| Add all new and changed files to the staging area |
| `git reset [file]` | unstage a file while retaining the changes in working directory |
| `git diff` | diff of what is changed but not staged |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |
| `git fetch [alias]` | fetch down all the branches from that Git remote |

### TEMPORARY COMMITS

| Command | Description |
| ------- | ----------- |
| `git stash` | Save modified and staged changes |
| `git stash list` | list stack-order of stashed file changes |
| `git stash pop` | write working from top of stash stack |
| `git stash drop` | discard the changes from top of stash stack |


### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |

### REWRITE HISTORY
| Command | Description |
| ------- | ----------- |
| `git rebase [branch]` | apply any commits of current branch ahead of specified one |
| `git reset --hard [commit]` | clear staging area, rewrite working tree from specified commit |

### IGNORING PATTERNS

| Command | Description |
| ------- | ----------- |
| `logs/ *.notes pattern*/` | Save a file with desired paterns as .gitignore with either direct string 
matches or wildcard globs |
| `git config --global core.excludesfile [file]` | system wide ignore patern for all local repositories |
