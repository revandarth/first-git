# Creating and Merging Branches in Git

## Learning Objectives

In this lab, you'll learn:
- How to create a new branch using Git's `branch` command.
- How to switch between branches using Git's `checkout` command.
- How to merge changes from one branch into another using Git's `merge` command.

## Creating a New Branch

If you haven't already done so in the previous lab, here's how you create a new branch:

1. Type `git branch new-branch` in your terminal, replacing `new-branch` with the name you want for your new branch.
2. To see a list of all branches, type `git branch`. Git will show you a list of all branches, with a `*` next to the current branch.

## Switching Between Branches

To switch to another branch, you use the `checkout` command followed by the name of the branch. Here's how:

1. Type `git checkout other-branch` in your terminal, replacing `other-branch` with the name of the branch you want to switch to.
2. If you type `git branch` again, you'll see that the `*` has moved to the branch you switched to.

## Merging Changes

If you have made changes in one branch and want to integrate them into another branch (usually the `master` or `main` branch), you can do so using the `merge` command. Here's how:

1. First, switch to the branch that you want to merge into (usually `master` or `main`).
2. Type `git merge other-branch` in your terminal, replacing `other-branch` with the name of the branch you want to merge from.
3. Git will merge the changes from the other branch into the current branch.

## Next Steps

Now that you've learned how to create and merge branches, you're ready for the managing merges challenge. Move on to the next lab, [Managing Merges Challenge](LINK_TO_NEXT_LAB), to test your new skills.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- [Your First Commit in Git](first-commit.md)
- [Using Branches in Git](branchs.md)
- [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- Creating and Merging Branches in Git
- [Managing Merges Challenge](merge-challenge.md)
- [Working with diff](git-diff.md)
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)
