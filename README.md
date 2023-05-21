# DevOps-Assignment1

Here are the steps to perform various actions in a Git repository:

1. Create a Repository:
   - Initialize a new repository locally: `git init`
   - Create a new repository on a remote Git hosting service (e.g., GitHub, GitLab)

2. Create Branches:
   - Create a new branch: `git branch <branch-name>`
   - Switch to the new branch: `git checkout <branch-name>`
   - Create and switch to a new branch in one step: `git checkout -b <branch-name>`

3. Perform Commit, Push, Pull:
   - Stage changes for commit: `git add <file(s)>`
   - Commit changes: `git commit -m "Commit message"`
   - Push changes to a remote branch: `git push origin <branch-name>`
   - Pull changes from a remote branch: `git pull origin <branch-name>`

4. Fork a Project, Open and Merge Pull Request:
   - Fork a repository on the Git hosting service (e.g., GitHub)
   - Clone the forked repository locally: `git clone <forked-repo-url>`
   - Create a new branch for your changes: `git checkout -b <branch-name>`
   - Make and commit the desired changes to the branch
   - Push the changes to your forked repository: `git push origin <branch-name>`
   - Open a pull request from your branch on the original repository
   - Review and discuss the changes in the pull request
   - Merge the pull request into the original repository if approved

5. Merge and Rebase:
   - Merge branches: `git merge <branch-name>`
   - Rebase branches: `git rebase <branch-name>`

6. Squashing Commits:
   - Interactively rebase to squash commits: `git rebase -i <commit>`
   - Follow the instructions to squash or combine commits

7. Delete Branches:
   - Delete a local branch: `git branch -d <branch-name>`
   - Delete a remote branch: `git push origin --delete <branch-name>`

Remember to replace `<branch-name>` with the actual branch name and `<commit>` with the desired commit reference. Additionally, make sure to configure the remote repository URL correctly when cloning, pushing, or pulling from a remote repository.
