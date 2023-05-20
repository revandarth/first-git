# Working with a Remote Repository on GitHub

## Learning Objectives

In this lab, you'll learn:
- How to create a remote repository on GitHub
- How to link a local Git repository to a remote repository on GitHub
- How to push changes from your local repository to the remote repository
- How to pull changes from the remote repository to your local repository

## Creating a Remote Repository on GitHub

1. Sign in to your GitHub account. If you do not have an account, you can create one for free at [GitHub](https://github.com/).
2. Click the '+' button in the upper right-hand corner and select 'New repository'.
3. Fill in the repository name, description (optional), and decide whether you want the repository to be public (visible to everyone) or private (visible only to you and people you invite).
4. Click 'Create repository'.

## Linking a Local Repository to a Remote Repository

1. Open your terminal and navigate to your local Git repository.
2. Type `git remote add origin URL_OF_YOUR_GITHUB_REPOSITORY`, replacing `URL_OF_YOUR_GITHUB_REPOSITORY` with the URL of the repository you created on GitHub. You can find this URL on the main page of your GitHub repository.
3. Verify that the remote repository has been added by typing `git remote -v` in your terminal. You should see the URL of your GitHub repository listed as the 'origin'.

## Pushing Changes to the Remote Repository

1. Make some changes in your local repository and commit them.
2. Type `git push origin master` in your terminal to push your changes to the master branch of the remote repository.

## Pulling Changes from the Remote Repository

1. Make some changes on the GitHub website and commit them.
2. Type `git pull origin master` in your terminal to pull the changes from the master branch of the remote repository to your local repository.

## Next Steps

Now that you've learned how to work with a remote repository on GitHub, you're ready to collaborate with others on larger projects. Continue practicing and exploring more advanced features of Git and GitHub to enhance your skills.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- [Your First Commit in Git](first-commit.md)
- [Using Branches in Git](branchs.md)
- [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- [Creating and Merging Branches in Git](merge-branch.md)
- [Managing Merges Challenge](merge-challenge.md)
- [Working with diff](git-diff.md)
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)
- Working with a Remote Repository on GitHub ← You are here
