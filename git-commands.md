## Git Local SetUp

* Check git version

`git -v`

* If git is not installed

`sudo apt update`

`sudo apt install git`

* Setup git configuration

`git config --global user.name "your_username"`

`git config --global user.email "name@example.com"`

## Git Commands

| Command | Usage | Example |
|-------|-----------|---------|
| `git init` | initialize a repo inside directory | `git init` |
| `git clone <url>` | clone an existing repo | `git clone https://github.com/Afroz-J-Shaikh/90DaysOfDevOps.git` |
| `git add file` | add untrack files | `git add demo.txt` |
| `git commit` | make a commit | `git commit -m "added demo.txt"` |
| `git reset file` | unstrack a file | `git reset demo.txt` |
| `git status` | check if anything to commit/add | `git status` |
| `git log` | check commit history | `git log` |
| `git revert commit-id` | creates new commit that undoes changes made by given commit | `git revert 4ae73` |
| `git reset commit-id` | reset head back till given commit id | `git reset 4ae73` |
| `git branch` | list all branches | `git branch` |
| `git switch <branch>` | switch branches | `git switch feature-1` |
| `git checkout -b <branch>` | create and switch to a branch | `git checkout -b feature-2` |
| `git branch -D <branch>` | delete a branch | `git branch -D feature-2` |
| `git rebase <branch>` | creates a linear history for current branch | `git rebase master` |
| `git log --oneline --graph --all` | shows history of all branches in graph | `git log --oneline --graph --all` |
| `git branch -D <branch>` | delete a branch | `git branch -D feature-2` |


