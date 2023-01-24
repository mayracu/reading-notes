# Revisions and the Cloud

## Practicing with Git

Today I synced my github Reading Notes repo to my local computer. Now I can make changes from a text editor in my computer and use a terminal to ACP my changes.

ACP stands for Add, Commit and Push. This means that every time I make a change in my text editor, I'll need to save the changes, go to my terminal, **add** the changes to my local repository, **commit** the changes and **push** them.

**Important:** After syncing my remote repository with my computer, I shouldn't make any more changes on GitHub. Any change I make to my repository it has to be made using my local master branch.

## Why is Git important?

- Git is a Distributed Version Control System (DVCS) that allows developers to save changes of their projects in a file system. Git creates snapshots of the different versions of a project, and stores references of these snapshots.

- Git makes it possible to track changes made to any file or directory.

## Status of a File

1. After a file has been edited, Git flags it as modified.
2. The modified file is staged.
3. Then, the staged changes are commited.

## Check the Status of a file

It's recommended to check the status using the `git status` command.

## Steps to ACP a file

    git add filename
    git status
    git commit -m "made change a,b,c"
    git status
    git push origin master
    git status

## Things I want to know more about

- Coding with VS Studio
- How to use features in a text editor.

*References:*

[https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#6_2](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#6_2)
