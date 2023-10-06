# Git and GitHub

## Git 

### What is git?
- git is a version control system that allows you to track changes to files over time.
-  It is a distributed version control system, which means that the entire codebase and history is available on every developer's computer, which allows for easy branching and merging.

## Why use git?
- Imagine you are working on a project with a team of developers.
- You are all working on the same codebase, and you all need to be able to make changes to the codebase.
- How do you make sure that you don't overwrite each other's changes?
- How do you make sure that you can revert to a previous version of the codebase if you need to?
- How do you make sure that you can easily merge your changes with your teammates' changes?

#### To Remember
- For a team to achieve the goals and objectives of a project, they need to be able to work together.
- There should not be any kind of friction between team members.



for the above reasons, we use git and it is not a black box. It is a tool that we can use to help us manage our codebase.Git makes the lives of developers easier by allowing them to track changes to their codebase over time.


### Basics Commands

- `git init` to intialize a git repository in the current directory.
- `git status` to check the status of the repository.
- `git add <file>` to add a file to the staging area.
- `git rm --cached <file>` to remove a file from the staging area.
- `git commit -m "message"` to commit the changes to the repository.
- `git revert <commit-hash>` to revert a commit.
- `git log` to view the commit history.
- `git diff` to view the changes made to the file.
- `git branch <branch-name>` to create a new branch.
- `git checkout <branch-name>` to switch to a branch.
- `git merge <branch-name>` to merge a branch into the current branch.
- `git remote add <remote-name> <remote-url>` to add a remote repository.
- `git push <remote-name> <branch-name>` to push changes to a remote repository.
- `git pull <remote-name> <branch-name>` to pull changes from a remote repository.
- `git clone <remote-url>` to clone a remote repository.


### References

- https://phoenixnap.com/kb/how-git-works


## GitHub

Github is a web-based hosting service for git repositories.Github is not the only single place on earth to host git repositories. There are other services like gitlab, bitbucket, etc.

### Creating a account in github

- go to github.com
- click on sign up
- enter your details
- click on create account
- verify your email address
- you are good to go

### User account vs Organization account

- User account is for personal use.
- Organization account is for team use.

## Working with remote repositories

### What is a remote repository?

In github there will be 100s and 1000s of repositories. Each repository will have a unique url or address. This url is called a remote url.

for example: 

- lets say there is organization called `PoineerClub` and it has a repository called `git_learning`. The url for this repository is `


![Alt text](./sc/scrnli_10_6_2023_9-34-43%20AM.png "a title")

- And lets say you want to add your meaningful contribution to this repository
- So how do yo do that ?
- Before adding anything that you want to add to this repository,the first and foremost thing you need this repository in your local machine.
- You don't directly add your contribution to this repository. You first add your contribution to your local repository and then you push your changes to the remote repository.

### Settng up the remote repository

- go to the repository that you want to contribute to.
- click on the fork button on the top right corner of the repository.
- this will create a copy of the repository in your github account.
- now you have a copy of the repository in your github account.
- now you need to clone this repository to your local machine.
- click on the code button and copy the url.
- now go to your terminal and type `git clone <url>`
- now you have a copy of the repository in your local machine.


### Adding your contribution to the remote repository

- I know you are eager to add your contribution to the repo you have cloned 
- But wait a minute. You need to create a branch first.
- This is because you don't want to add your contribution to the main branch of the repository. You want to add your contribution to a separate branch.
- This is because you don't want to mess up the main branch of the repository.
- So you create a branch and add your contribution to that branch.

### Creating a branch

- go to your terminal and type `git branch <branch-name>`
- now you have created a branch.
- now you need to switch to that branch.
- go to your terminal and type `git checkout <branch-name>`

### Adding your contribution to the branch

- now you can add your contribution to the branch.
- once you have added your contribution, you need to commit your changes.
- go to your terminal and type `git add filename` to add the file to the staging area.
- go to your terminal and type `git commit -m "message"` to commit the changes to the repository.
- now you have committed your changes to the repository.
- now you need to push your changes to the remote repository.

### Pushing your changes to the remote repository
 
- Great work so far. You have added your contribution to the branch. 
- Now you need to some how send the changes that you have made in your local repository to the remote repository.
- This is called pushing your changes to the remote repository.
- go to your terminal and type `git push origin <branch-name>`


### Creating a pull request

- Now you have pushed your changes to the remote repository.
- But wait a minute. You have pushed your changes to the branch in your remote repository.
- You want to add your changes to the main branch of the remote repository.
- So how do you do that ?
- You create a pull request.
- A pull request is a request to the owner of the repository to add your changes to the main branch of the repository.
- go to your github account and click on the pull request button.
- click on the create pull request button.
- now you have created a pull request.
- now the owner of the repository will review your changes and if he/she is happy with your changes, he/she will merge your changes to the main branch of the repository.



--------------------------------------- The End ---------------------------------------------------------

# What the heck ? have you every heard the word "The End" in software development ?
# Software development is like a never ending process. There is no end to it.

`Encance Evolve and Enjoy`

# Happy Coding !
