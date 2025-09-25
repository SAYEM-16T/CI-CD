# 📌 Useful Git Commands List

| Command | Description |
|---------|-------------|
| `git init` * | Initialize a local Git repository |
| `git clone repo_url` * | Clone a public repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Clone a private repository |
| `git status` * | Check the status of changes |
| `git add [file-name]` | Add a file to the staging area |
| `git add -A` * | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` *  | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |
| `git branch` * | List of branches (the asterisk denotes the current branch) |
| `git branch -a` * | List all branches (local and remote) |
| `git branch [branch name]` * | Create a new branch |
| `git branch -d [branch name]` * | Delete a branch |
| `git branch -D [branch name]` * | Force delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` * | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` * | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |
| `git push origin [branch name]` * | Push a branch to your remote repository |
| `git push -u origin [branch name]` * | Push changes to remote and set upstream (first time) |
| `git push` * | Push changes (after upstream set) |
| `git pull` * | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from a remote branch |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Change remote repo URL to SSH |
| `git log` | View commit history |
| `git log --summary` | View detailed commit history |
| `git log --oneline` | View compact commit history |
| `git diff [source branch] [target branch]` | Preview changes before merging |
| `git revert <commit-id>` | Revert commit changes |
| `git config --global user.name "your_username"` | Set global username |
| `git config --global user.email "your_email@example.com"` | Set global email address |
| `git config --global --list` | Show global Git configuration |
