# Git Commands and Their Purpose

**Name:** Atman Patel  
**Roll Number:** BT25CSE180  
**Section:** CSE C

## 1. Git Commands Used

| Command | Purpose |
|---|---|
| `git clone URL` | Clones a remote repository to the local computer. |
| `cd folder-name` | Navigates into a folder. |
| `mkdir folder-name` | Creates a new folder. |
| `git status` | Displays the current status of the repository. |
| `git add .` | Adds all modified and new files to the staging area. |
| `git add filename` | Adds a specific file to the staging area. |
| `git commit -m "message"` | Saves staged changes with a descriptive message. |
| `git push origin main` | Pushes local commits to the main branch on GitHub. |
| `git pull origin main` | Fetches and integrates changes from the remote main branch. |
| `git branch` | Lists all local branches. |
| `git checkout -b branch-name` | Creates a new branch and switches to it. |
| `git checkout main` | Switches to the main branch. |
| `git merge branch-name` | Merges the specified branch into the current branch. |
| `git log --oneline` | Displays commit history in a compact format. |
| `git remote -v` | Displays the configured remote repository URLs. |

## 2. Git Workflow Followed

1. Created a repository on GitHub.
2. Cloned the repository to the local computer.
3. Created separate folders for each exercise.
4. Added source code and documentation files.
5. Used `git add` to stage the changes.
6. Used `git commit` to save changes.
7. Created separate branches for exercises.
8. Pushed branches to GitHub using `git push`.
9. Created pull requests and merged them into the main branch.

## 3. Merge Conflict and Resolution

A merge conflict occurs when Git cannot automatically combine changes made to the same part of a file in different branches.

### Steps to Resolve a Merge Conflict

1. Identify the file containing the conflict.
2. Open the conflicting file in VS Code.
3. Examine the changes from both branches.
4. Choose the correct changes or combine both versions.
5. Remove the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
6. Save the file.
7. Stage the resolved file using `git add`.
8. Commit the resolved changes.

### Conclusion

Through this assignment, I learned the basic Git commands and GitHub workflow, including cloning repositories, staging files, committing changes, branching, merging, and creating pull requests.