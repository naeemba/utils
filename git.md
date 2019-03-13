### Commits that are new in master since I created this branch
`git log [current_branch]..origin/master`

### Details of commits that are new in master since I created this branch
`git diff [current_branch]...origin/master`
#### Navigate options: [stackoverflow](https://stackoverflow.com/a/8640894/2443849)
```Next line             : return
Next page             : space bar
Previous page         : w
Quit viewing the diff : q
Help                  : h
```

### Commit merge conflicts with default commit message [stackoverflow](https://stackoverflow.com/a/36189488/2443849)
`git commit --no-edit`

### List of all branches (remote and local)
`git branch -a`
### To update the local list of remote branches: [stackoverflow](https://stackoverflow.com/a/36358502/2443849)
`git remote update origin --prune`

### To view changes have made by a commit [stackoverflow](https://stackoverflow.com/a/17563740/2443849)
`git show [COMMIT_ID]`

### To checkout remote branch [stackoverflow](https://stackoverflow.com/questions/1783405/how-do-i-check-out-a-remote-git-branch)
`git checkout -t [Remote branch name]`

### Beautiful one line git logs [Ma.ttias.be](https://ma.ttias.be/pretty-git-log-in-one-line/)
`git log --pretty=oneline`\
 or:\
`git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit`\
or create an alias for that:\
`git config --global alias.logline "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"`\
`git logline`
##### Other pretty logs
`git log --pretty=format:"%Cred%h%Creset %C(yellow)%ad%Creset %s %Cgreen%an%Creset"`

## Useful websites
[Git Explorer](https://gitexplorer.com/)
