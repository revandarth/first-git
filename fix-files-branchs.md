# Fixing Your Mistakes: Files and Branches in Git

## Learning Objectives

In this lab, you'll learn:
- How to unstage changes using Git's `reset` command.
- How to revert changes to a file using Git's `checkout` command.
- How to delete a branch using Git's `branch -d` command.

## Unstaging Changes

If you've staged changes that you don't want to commit, you can unstage them using the `reset` command. Here's how:

1. Type `git reset HEAD file` in your terminal, replacing `file` with the name of the file you want to unstage.
2. If you type `git status`, you'll see that the file is no longer staged for commit.

## Reverting Changes to a File

If you've made changes to a file that you want to discard, you can revert the file to its state at the last commit using the `checkout` command. Here's how:

1. Type `git checkout -- file` in your terminal, replacing `file` with the name of the file you want to revert.
2. If you type `git status`, you'll see that the changes to the file have been discarded.

## Deleting a Branch

If you've finished with a branch and want to delete it, you can do so using the `branch -d` command. Here's how:

1. First, make sure you're not currently on the branch you want to delete. If you are, switch to a different branch using `git checkout other-branch`.
2. Type `git branch -d branch-to-delete` in your terminal, replacing `branch-to-delete` with the name of the branch you want to delete.
3. If you type `git branch`, you'll see that the branch has been deleted.

## Next Steps

Now that you've learned how to fix mistakes in Git, you're ready for your first branch challenge. Move on to the next lab, [Creating Your First Branch Challenge](LINK_TO_NEXT_LAB), to test your new skills.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- [Your First Commit in Git](first-commit.md)
- [Using Branches in Git](branchs.md)
- Fixing Your Mistakes: Files and Branches in Git
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- [Creating and Merging Branches in Git](merge-branch.md)
- [Managing Merges Challenge](merge-challenge.md)
- [Working with diff](git-diff.md)
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)