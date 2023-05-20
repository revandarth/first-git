# Your First Commit in Git

## Learning Objectives

In this lab, you'll learn:
- How to create and stage changes for your first commit using Git's `add` command.
- How to commit your staged changes using Git's `commit` command.
- The significance of a Git commit message.

## Preparing for Your First Commit

Once you've initialized your Git repository, it's time to make your first commit. But before you do that, you need to make some changes to your project that you want Git to track.

1. Create a new file or modify an existing file in your repository.
2. Check the status of your repository by typing `git status` in your terminal. This command will show you which changes Git has detected.

## Staging Changes for Commit

When you're ready to save your changes, you need to stage them for commit.

1. Stage your changes by typing `git add .` in your terminal. The `.` tells Git to stage all changes in the repository. If you only want to stage specific files, you can list them instead of the `.`.
2. Run `git status` again. This time, Git will show you which changes are staged for commit.

## Making Your First Commit

Now you're ready to make your first commit.

1. Type `git commit -m "Your commit message"` in your terminal. Replace "Your commit message" with a brief description of the changes you made.
2. Run `git log`. This command shows you a history of all the commits you've made. Your latest commit should be at the top of the list.

## Understanding Commit Messages

A commit message should be a clear and concise summary of the changes made in the commit. Good commit messages allow other developers (and your future self) to understand why changes were made. Here are some tips for writing good commit messages:

- Start with a short summary (50 characters or less), then provide a more detailed description if necessary.
- Use the imperative mood ("Add README file" not "Added README file").
- Explain what the commit does, not how or why. If the how or why is complicated, that information could probably go in code comments or documentation.

## Next Steps

Now that you've made your first commit, you're ready to learn about branches. Move on to the next lab, [Using Branches in Git](LINK_TO_NEXT_LAB), to learn more.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- Your First Commit in Git
- [Using Branches in Git](branchs.md)
- [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- [Creating and Merging Branches in Git](merge-branch.md)
- [Managing Merges Challenge](merge-challenge.md)
- [Working with diff](git-diff.md)
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)