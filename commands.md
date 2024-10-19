Here are some basic Git commands:

1. Setting up Git
git init
Initializes a new Git repository in the current directory.

git clone <repository-url>
Clones an existing Git repository to your local machine.

2. Configuration
git config --global user.name "Your Name"
Sets your username for Git commits.

git config --global user.email "your.email@example.com"
Sets your email address for Git commits.

3. Basic Workflow
git status
Shows the current state of your working directory (files that are staged, unstaged, or untracked).

git add <file>
Stages a specific file for the next commit.

git add .
Stages all changes (new, modified, and deleted files) for the next commit.

git commit -m "Commit message"
Commits the staged changes with a descriptive message.

git push
Pushes the committed changes to a remote repository (e.g., GitHub, GitLab).

git pull
Fetches and merges changes from a remote repository into your local repository.

4. Branching
git branch
Lists all branches in your repository.

git branch <branch-name>
Creates a new branch.

git checkout <branch-name>
Switches to the specified branch.

git checkout -b <branch-name>
Creates and switches to a new branch in one command.

git merge <branch-name>
Merges the specified branch into the current branch.

5. History and Logs
git log
Displays the commit history.

git diff
Shows changes between your working directory and the last commit.

git reset --hard <commit>
Resets your repository to a specific commit, discarding all changes.

6. Undo Changes
git restore <file>
Discards changes in a working directory (to undo modifications).

git reset <file>
Unstages a file but keeps its changes in the working directory.

These commands should help you manage and navigate a Git repository efficiently.
