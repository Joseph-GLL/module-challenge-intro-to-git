## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a SCM (source code management system) that allows us to make branches for multiple individuals to work on with their local machines to then allow for review and merge of the code that was worked on to fix bugs or add new features to the main branch.
2. What is the difference between Git and GitHub?
Git is the underlying system or terminal that allows us to make branches and edits to a repo, Github is the cloud repository that holds all the branches, changes and data.
3. Why do we create a branch?
We create branches to make sure there is version control, the branch allows each developer to make changes and run test before merging to the main branch.
4. What is the purpose of a Pull Request?
To begin the process that will merge your code that was added/created in your branch(local copy) back to the main branch.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
The command is "git checkout -b 'branch-Name'", to switch back to the main branch you would enter "git checkout -b main"
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch - checks to see if any changes have been made to the remote repo but doesn't actually update the local repo with those changes
git merge - only used if git fetch was run and you would like to merge the available changes from the remote repo to the local branch
git pull - updates local branch with most recent saved changes that are in remote repo(github - cloud repository); performs the same actions that running git fetch then git merge would do, almost like a shortcut
7. What is a merge conflict?
Merge conflicts happen when the branches you are trying to merge have had changes applied to them in the same file, git doesn't know which branch to use.
8. How do you resolve a merge conflict?
You need to find the conflict that each branch encountered and review the sections with your team (or yourself if solo proj) to make changes so that everything runs properly and no longer reports conflicts.
