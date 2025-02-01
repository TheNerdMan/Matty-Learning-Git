# Exercise 1: Creating Your First Repository

This exercise will guide you through creating and managing your first Git repository.

## Steps

1. Open your terminal or command prompt

2. Create a new directory:
   ```bash
   mkdir my-first-repo
   cd my-first-repo
   ```

3. Initialize the Git repository:
   ```bash
   git init
   ```

4. Create a new file called `hello.txt`:
   ```bash
   echo "Hello, Git!" > hello.txt
   ```

5. Check the status of your repository:
   ```bash
   git status
   ```

6. Stage the file:
   ```bash
   git add hello.txt
   ```

7. Commit the file:
   ```bash
   git commit -m "Add hello.txt"
   ```

8. Create a GitHub account if you haven't already

9. Create a new repository on GitHub (don't initialize it with a README)

10. Connect your local repository to GitHub:
    ```bash
    git remote add origin YOUR_REPOSITORY_URL
    ```

11. Push your changes to GitHub:
    ```bash
    git push -u origin main
    ```

## Expected Output
- A new repository initialized locally
- A committed file
- A GitHub repository connected to your local repository
- Your code pushed to GitHub

## Verification
- Check your GitHub repository - you should see your hello.txt file there
- Run `git log` to see your commit history