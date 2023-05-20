# Managing Merges Challenge

## Challenge Objectives

In this challenge, you'll demonstrate your understanding of managing merges in Git by:

- Creating two different branches
- Making distinct changes on each branch
- Merging both branches into the master branch

## Challenge Instructions

1. Initialize a new Git repository if you haven't already. You can do this by typing `git init` in your terminal.
2. Create a new file in your repository and add some content to it.
3. Stage and commit your changes.
4. Create two new branches called `feature1` and `feature2`. You can do this by typing `git branch feature1` and `git branch feature2` in your terminal.
5. Switch to the `feature1` branch by typing `git checkout feature1`.
6. Make some changes to the file you created earlier.
7. Stage and commit these changes.
8. Repeat steps 5-7 for the `feature2` branch.
9. Switch back to the `master` branch by typing `git checkout master`.
10. Merge both `feature1` and `feature2` into `master` using the `git merge` command.

## Challenge Verification

To verify that you've successfully completed this challenge:

1. Type `git log` in your terminal. You should see the commits from both `feature1` and `feature2`.
2. Open the file you've been editing. It should contain the changes made in both feature branches.

## Next Steps

Congratulations on completing the managing merges challenge! Now you're ready to learn more about working with diff in Git. Move on to the next lab, [Working with diff](LINK_TO_NEXT_LAB), to learn more.

## Interactive Set

This lab is part of an interactive set. Here's what's coming up next:
- [Your First Git Repository](README.md)
- [Your First Commit in Git](first-commit.md)
- [Using Branches in Git](branchs.md)
- [Fixing Your Mistakes: Files and Branches in Git](fix-files-branchs.md)
- [Creating Your First Branch Challenge](first-branch-challenge.md)
- [Creating and Merging Branches in Git](merge-branch.md)
- Managing Merges Challenge
- [Working with diff](git-diff.md)
- [Creating a Git Log Challenge](git-log-challenge.md)
- [Testing Your Knowledge of Git: Final Challenge](final-challenge.md)