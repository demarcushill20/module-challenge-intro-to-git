## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is a version control system
2. What is the difference between Git and GitHub?
Git is a tool, while GitHub is a platform built around that tool.
3. Why do we create a branch?
Branches allow you to isolate development work from the main codebase. You can make changes to a branch without affecting the rest of the code
4. What is the purpose of a Pull Request?
It's a way to submit changes you've made in a branch to a main branch (often called "master") for review and potential merging.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
To switch between branches in Git, you can use the "git checkout" command followed by the name of the branch you want to switch to.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch: This command downloads new data from a remote repository, but it doesn't automatically merge the changes into your local repository. Instead, it fetches all the changes and stores them in your local repository, allowing you to review the changes and manually merge them into your local branches using the git merge command.

git merge: This command is used to merge changes from one branch into another. For example, if you have changes in a branch called "feature", you can merge those changes into your "main" branch using the command git merge feature. This command will merge the changes from the "feature" branch into the current branch.

git pull: This command combines the functionality of git fetch and git merge into a single command. When you run git pull, Git will fetch changes from a remote repository and then automatically merge them into your local branches. The exact behavior of git pull depends on the Git configuration, but by default it merges the changes from the remote branch that is tracking your current branch.
7. What is a merge conflict?
A merge conflict occurs when Git is unable to automatically merge changes from multiple branches into a single branch. This can happen when both branches have made changes to the same lines of code, and Git is unable to determine which changes should be kept.
8. How do you resolve a merge conflict?
Resolving a merge conflict in Git involves editing the conflicting files to remove the conflict markers and deciding which changes should be kept.