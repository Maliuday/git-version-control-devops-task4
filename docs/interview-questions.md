# Git Interview Questions and Answers

## 1. What is Git?
Git is a distributed version control system used to track changes in source code and collaborate with developers.

## 2. What is the difference between merge and rebase?
- Merge combines changes from one branch into another and preserves branch history.
- Rebase moves commits onto another base commit and creates a linear history.

## 3. What is a Pull Request?
A Pull Request is a request to review and merge changes from one branch into another branch on GitHub.

## 4. How do you resolve merge conflicts?
1. Open the conflicting files.
2. Identify the conflicting changes.
3. Edit the file and keep the required code.
4. Stage the resolved file.
5. Commit the changes or complete the merge.

## 5. What are Git tags?
Git tags are references used to mark specific commits, commonly for version releases such as v1.0.0.

## 6. What is Git workflow?
Git workflow is a process developers follow to create branches, make commits, review changes, merge code, and maintain project history.

## 7. Explain git stash.
`git stash` temporarily saves uncommitted changes so we can work on another task without committing the current changes.

Useful commands:
- `git stash`
- `git stash list`
- `git stash pop`

## 8. What is the use of .gitignore?
`.gitignore` tells Git which untracked files and directories should be excluded from version control, such as logs, temporary files, and secrets.
