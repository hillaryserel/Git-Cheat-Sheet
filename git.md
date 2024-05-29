# Git Cheat Sheet

## Create a new Repository
- `git init`: Initialize a new Git repository.
- `git clone <repository-url>`: Clone a repository into a new directory.

## Observe your Repository
- `git status`: Show the working directory status.
- `git diff`: Show the changes to files not yet staged.
- `git diff --cached`: Show all staged files.
- `git diff HEAD'`: Show all staged and unstaged file changes.
- `git diff commit1 commit2`: Show the changes between two commits.
- `git blame [file]`: Show the change dates and authors for a file.
- `git show [commit]:[file]` : Show the file changes for a commit id and for a file.
- `git log [file]`: Show full change history
- `git log -p [file/history]`: Show change history for a file/directory including diffs.

# Branching
- `git branch`: List all branches.
- `git branch -av`: List all branches, local and remote branches
- `git checkout <branch-name>`: Switch to a specific branch.

## Merge branches
- `git checkout branch_b`
- `git merge branch_a`

- `git merge <branch-name>`: Merge a branch into the current branch.
- `git branch -d <branch-name>`:Delete the current branch

## Commit
- `git add <file>`: Add a file to the staging area.
- `git add.`:Stage all changed files ready to be committed
- `git commit -m "message"`: Commit staged changes with a message.
- `git reset[file]`: Unstages file keeping the file changes
- `git reset --hard`: Revert everything to the last commit

## Synchronization
- `git fetch`: Get the latest commit from origin(no merge)
- `git pull`: Get the latest changes from the origin and merge
- `git pull --rebase`: Get the latest changes from origin and rebase
- `git push`: Push local changes to the origin

## Help
- `git command --help`: Display help information
