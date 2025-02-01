# Exercise 2: Branching and Merging

Learn how to work with branches and merge changes in Git.

## Steps

1. Make sure you're in your repository:
   ```bash
   cd my-first-repo
   ```

2. Create and switch to a new branch:
   ```bash
   git checkout -b feature-branch
   ```

3. Edit hello.txt to add a new line:
   ```bash
   echo "Learning about branches!" >> hello.txt
   ```

4. Stage and commit your changes:
   ```bash
   git add hello.txt
   git commit -m "Update hello.txt in feature branch"
   ```

5. Switch back to the main branch:
   ```bash
   git checkout main
   ```

6. Merge your feature branch:
   ```bash
   git merge feature-branch
   ```

7. Push changes to GitHub:
   ```bash
   git push origin main
   ```

## Expected Output
- A new branch created and used
- Changes made and committed in the feature branch
- Changes successfully merged to main branch
- Updated code pushed to GitHub

## Verification
- Run `git branch` to see all branches
- Check the content of hello.txt
- Look at your commit history with `git log --oneline --graph`