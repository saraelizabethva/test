## Basic Git Commands

Here is a quick reference for some of the most common Git commands:

### Setup and Initialization
- `git init`: Initialize a local Git repository.
- `git clone <url>`: Clone a remote repository to your local machine.

### Staging and Committing
- `git status`: Check the status of your working tree (staged, unstaged, and untracked files).
- `git add <file>`: Add a file to the staging area.
- `git add .` (or `git add -A`): Add all changed files to the staging area.
- `git commit -m "message"`: Commit your staged changes with a descriptive message.

### Branching and Merging
- `git branch`: List all local branches.
- `git checkout -b <branch-name>`: Create a new branch and switch to it immediately.
- `git checkout <branch-name>` (or `git switch <branch-name>`): Switch to an existing branch.
- `git merge <branch-name>`: Merge the specified branch's history into the current branch.

### Remote Repositories
- `git push origin <branch-name>`: Push your local branch commits to the remote repository.
- `git pull`: Fetch and merge changes from the remote repository to your current local branch.
- `git fetch`: Download changes from the remote repository without merging them.
- `git remote -v`: List the current remote repositories.

### History and Examination
- `git log`: View the commit history.
- `git diff`: Show changes between your working tree and the index (staged area).