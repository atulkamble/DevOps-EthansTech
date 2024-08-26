Here are some basic Git commands that are essential for managing a Git repository:

### 1. *git init*
- Initializes a new Git repository in the current directory.
  bash
  git init
  

### 2. *git clone*
- Clones an existing repository into a new directory.
  bash
  git clone https://github.com/username/repository.git
  

### 3. *git status*
- Shows the status of changes in the working directory.
  bash
  git status
  

### 4. *git add*
- Stages changes (files) to be committed.
  bash
  git add filename
  
- To stage all changes:
  bash
  git add .
  

### 5. *git commit*
- Records the staged changes with a message describing the changes.
  bash
  git commit -m "Your commit message"
  

### 6. *git push*
- Uploads local commits to the remote repository.
  bash
  git push origin branch-name
  

### 7. *git pull*
- Fetches and integrates changes from the remote repository to the local branch.
  bash
  git pull origin branch-name
  

### 8. *git branch*
- Lists all branches or creates a new branch.
  bash
  git branch          # List branches
  git branch branch-name  # Create a new branch
  

### 9. *git checkout*
- Switches to a different branch or commit.
  bash
  git checkout branch-name  # Switch branch
  

### 10. *git merge*
- Merges changes from one branch into the current branch.
  bash
  git merge branch-name
  

### 11. *git log*
- Shows the commit history.
  bash
  git log
  

### 12. *git remote*
- Manages connections to remote repositories.
  bash
  git remote add origin https://github.com/username/repository.git  # Add remote
  git remote -v  # List remote connections
  

### 13. *git reset*
- Unstages files or resets the current branch to a specific commit.
  bash
  git reset filename  # Unstage a file
  git reset --hard commit-hash  # Reset to a specific commit
  

### 14. *git rm*
- Removes files from the working directory and stages the deletion.
  bash
  git rm filename
  

### 15. *git config*
- Sets configuration options for Git, such as username and email.
  bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  

These commands will help you perform basic Git operations, from initializing repositories to managing branches and commits.