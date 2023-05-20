# Using Branches in Git

## Learning Objectives

In this lab, you'll learn:
- What a Git branch is and why it's useful.
- How to create a new branch using Git's `branch` command.
- How to switch between branches using Git's `checkout` command.

## Understanding Git Branches

In Git, a branch is essentially a pointer to a specific commit. Branches are useful for isolating changes for specific features or experiments, keeping them separate from your main or 'master' branch. Once the changes are finalized and tested, they can be merged back into the master branch.

## Creating a New Branch

To create a new branch, you use the `branch` command followed by the name of the new branch. Here's how:

1. Type `git branch new-branch` in your terminal, replacing `new-branch` with the name you want for your new branch.
2. To see a list of all branches, type `git branch`. Git will show you a list of all branches, with a `*` next to the current branch.

## Switching Between Branches

To switch to another branch, you use the `checkout` command followed by the name of the branch. Here's how:

1. Type `git checkout other-branch` in your terminal, replacing `other-branch` with the name of the branch you want to switch to.
2. If you type `git branch` again, you'll see that the `*` has moved to the branch you switched to.

## Next Steps

Now that you've learned how to create and switch between branches, you're ready to learn how to fix your mistakes using Git. Move on to the next lab, [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)), to learn more.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- [Your First Commit in Git](first-commit.md)
- Using Branches in Git ← You are here
- [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- [Creating and Merging Branches in Git](merge-branch.md)
- [Managing Merges Challenge](merge-challenge.md)
- [Working with diff](git-diff.md)
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)
- [Working with a Remote Repository on GitHub](remote-repository.md)

