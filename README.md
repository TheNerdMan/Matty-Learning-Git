# Learn Git and GitHub

Welcome to this hands-on tutorial for learning Git and GitHub! This repository is designed to help beginners understand the fundamentals of version control using Git and collaboration using GitHub.

## Table of Contents
1. [Setting Up](#setting-up)
2. [Basic Git Commands](#basic-git-commands)
3. [Working with GitHub](#working-with-github)
4. [Practical Exercises](#practical-exercises)
5. [Additional Resources](#additional-resources)

## Setting Up

### Installing Git
1. **Windows**: Download and install Git from [git-scm.com](https://git-scm.com/)
2. **macOS**: Install using Homebrew: `$ brew install git`
3. **Linux**: Install using package manager: `$ sudo apt-get install git` (Ubuntu/Debian)

### Configuring Git
```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "your.email@example.com"
```

## Basic Git Commands

### Creating and Managing Repositories
0. **Make a directory**
   ```bash
   $ mkdir git-lesson
   $ cd git-lesson
   ```

1. **Initialize a new repository**
   ```bash
   $ git init
   ```

2. **Check repository status**
   ```bash
   $ git status
   ```

3. **Stage changes**
   ```bash
   $ git add filename    # Stage specific file
   $ git add .          # Stage all changes
   ```

4. **Commit changes**
   ```bash
   $ git commit -m "Your commit message"
   ```

### Working with Branches
1. **Create a new branch**
   ```bash
   $ git branch branch-name
   ```

2. **Switch to a branch**
   ```bash
   $ git checkout branch-name
   $ # or use the newer command
   $ git switch branch-name
   ```

3. **Create and switch to a new branch**
   ```bash
   $ git checkout -b new-branch-name
   ```

## Working with GitHub

### Setting Up GitHub
1. Create a GitHub account at [github.com](https://github.com)
2. Set up SSH keys for secure communication with GitHub
   ```bash
   $ ssh-keygen -t ed25519 -C "your.email@example.com"
   ```

### Basic GitHub Operations
1. **Clone a repository**
   ```bash
   $ git clone repository-url
   ```

2. **Add a remote repository**
   ```bash
   $ git remote add origin repository-url
   ```

3. **Push changes**
   ```bash
   $ git push origin branch-name
   ```

4. **Pull changes**
   ```bash
   $ git pull origin branch-name
   ```

## Practical Exercises

Check out the exercises folder for hands-on practice:

1. [Exercise 1](exercises/exercise1.md) - Create your first repository
2. [Exercise 2](exercises/exercise2.md) - Learn branching and merging
3. [Exercise 3](exercises/exercise3.md) - Collaborate using Pull Requests

## Additional Resources
- [GitHub Documentation](https://docs.github.com)
- [Git Documentation](https://git-scm.com/doc)
- [Interactive Git Learning](https://learngitbranching.js.org/)
- [GitHub Skills](https://skills.github.com/)

## Common Issues and Solutions

### Merge Conflicts
When Git can't automatically merge changes, you'll need to resolve conflicts manually:
1. Open the conflicted files
2. Look for conflict markers (<<<<<<, =======, >>>>>>>)
3. Edit the file to resolve conflicts
4. Stage and commit the resolved files

### Undoing Changes
1. **Discard unstaged changes**
   ```bash
   $ git restore filename
   ```

2. **Unstage changes**
   ```bash
   $ git restore --staged filename
   ```

3. **Undo last commit**
   ```bash
   $ git reset HEAD~1
   ```

Remember: The best way to learn Git is by practicing. Don't be afraid to experiment in a test repository!