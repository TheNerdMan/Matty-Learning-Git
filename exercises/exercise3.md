# Exercise 3: Collaboration and Pull Requests

Learn how to collaborate with others using GitHub's Pull Request feature.

## Steps

1. Find a public repository to fork on GitHub
   - You can use: https://github.com/octocat/Spoon-Knife

2. Fork the repository by clicking the "Fork" button

3. Clone your fork locally:
   ```bash
   git clone YOUR_FORK_URL
   cd repository-name
   ```

4. Create a new branch for your changes:
   ```bash
   git checkout -b my-new-feature
   ```

5. Make some changes to the repository

6. Stage and commit your changes:
   ```bash
   git add .
   git commit -m "Add my new feature"
   ```

7. Push your branch to GitHub:
   ```bash
   git push origin my-new-feature
   ```

8. Go to GitHub and create a Pull Request:
   - Click "Pull Request"
   - Set base repository to the original repo
   - Write a description of your changes
   - Submit the Pull Request

## Expected Output
- A forked repository
- Local changes pushed to your fork
- A Pull Request created

## Verification
- Check your fork on GitHub
- Verify your Pull Request appears in the original repository
- Review the changes in the Pull Request