
# Git Commands Reference

## Repository Setup
- git init - Initialize a repository
- git clone URL - Clone a repository
- git status - Check repository status

## Branching
- git branch - List branches
- git branch dev - Create dev branch
- git switch dev - Switch branch
- git switch -c feature/docs - Create feature branch

## Commits
- git add . - Stage changes
- git commit -m "message" - Save changes
- git log --oneline - View commit history

## Remote Operations
- git remote -v - View remote URLs
- git push -u origin branch-name - Push branch
- git pull - Get latest changes
- git fetch - Fetch remote updates

## Merge and Rebase
- git merge branch-name - Merge a branch
- git rebase main - Reapply commits on main

## Stash
- git stash - Temporarily save changes
- git stash list - List stashes
- git stash pop - Restore latest stash

## Tags
- git tag v1.0.0 - Create a tag
- git tag - List tags
- git push origin v1.0.0 - Push a tag
