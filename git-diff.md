# Working with diff

## Learning Objectives

In this lab, you'll learn:
- How to view the differences between commits using Git's `diff` command.
- How to view the differences between the working directory and the staging area.

## Viewing Differences Between Commits

To view the differences between commits, you can use the `diff` command followed by the hashes of the two commits. Here's how:

1. Type `git log` in your terminal to see a list of all commits along with their hashes.
2. Type `git diff hash1 hash2` in your terminal, replacing `hash1` and `hash2` with the hashes of the two commits you want to compare. Git will show you the differences between the two commits.

## Viewing Differences Between the Working Directory and the Staging Area

You can also use the `diff` command to view the differences between the working directory and the staging area. Here's how:

1. Type `git diff` in your terminal. Git will show you the differences between the working directory and the staging area.

## Next Steps

Now that you've learned how to work with diff, you're ready for the creating a Git log challenge. Move on to the next lab, [Creating a Git Log Challenge](git-log-challenge.md), to test your new skills.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- [Your First Commit in Git](first-commit.md)
- [Using Branches in Git](branchs.md)
- [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- [Creating and Merging Branches in Git](merge-branch.md)
- [Managing Merges Challenge](merge-challenge.md)
- Working with diff ← You are here
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)
- [Working with a Remote Repository on GitHub](remote-repository.md)