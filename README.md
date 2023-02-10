# git-cheat-sheet

## What is Git:-
1. Git is a version control system
2. Git helps you keep track of your code changes
3. It is used to collaborate on code
4. Git and GitHub are different things

## Why Git:-
1. Over 70% of developers use Git!
2. Developers can work together from anywhere in the world
3. Developers can see the full histry of the project
4. Developers can revert to earlier versions of the project

## Features of Git :-

1. When a file is changed, added or deleted, it is considered modifie
2. You select the modified files you want to stage
3. The staged files are Committed, which prompts Git to store a permanent snapshot of the files
4. Git allows you to see the full history of every commit
5. You can revert back to any previous commit.
6. Git doesn't store a seperate copy of every file in every commit, but keeps track of changes made in each commit!

## What is GitHub :-

1. Git is not the same as GitHub.
2. GitHub makes tools that use Git.
3. GitHub is the largest host of source code in the world,

So, let’s Dive into the Details…!!

## Configuring Git for the first time :-

$${\color{green}git config -global user.name “[name]”}$$

$${\color{green}git config -global user.email “[email address]"}$$

This command sets the author name and email address respectively to be used with your commits.

## Git clone from GitHub :-

$${\color{green}git clone [url]}$$

Used to create an instance of the remote repository into your local repo.

## Initializing a :-

$${\color{green}git init}$$

This command is used to initialise a new repository.

Once done, now you have a hidden subdirectory called `.git` in your project directory that contains all of your necessary repository files.

## Staging files / Add Files and Commit changes to Git Repo :-

Staged files are files that are ready to be committed to the repository you are working on.

When you first add files to an empty repository, they are all untracked. To track them, you need to stage them, or add them to the staging environment

$${\color{green}git add [filename]}$$

This command adds specified files to the staging area (enviroment)

This command doesn't add `.gitignore` file by default

$${\color{green}git add .</span>}$$

This command adds all files to the staging area.

## Making a Commit :-

Commit all the changes with a commit message using the command

$${\color{green}git commit -m “[ Type in the commit message]” }$$

The first part of the command `git commit` tells Git that all the files staged are ready to be committed so it takes a perminent snapshot of the files. 

The second part `-m "first commit"` is the commit message.

$${\color{green}git commit -a}$$

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

## Status Checking

To check the working tree status, file details, use the command

$${\color{green}git status }$$

This command lists all the files that have to be committed.

## git log

If you want to view the commit details then use the command

$${\color{green}git log }$$

This command is used to list the version history for the current branch.

It will give you the result as the commit object, name of the author who made the changes, timestamp, and the changes.

## Git Branching :-

In Git a branch is a new/seperate version of the main repository.

Branches allows you to work on different parts of a project without impacting the main branch. When the work is complete, a branch can be merged with the main project

We can even switch between branches and work on different projects without them interferring with each other.

$${\color{green}git branch}$$

This command lists all the local branches in the current repository.

$${\color{green}git branch [branch name] }$$

This command creates a new branch.

$${\color{green}git checkout [branch name] }$$

This command is used to switch from one branch to another.

$${\color{green}git checkout -b [branch name]}$$

This command creates a new branch and also switches to it.

$${\color{green}git branch -d [branch name]}$$

Used to deletes an existing branch.

$${\color{green} git merge [branch]}$$

Us to merge a specified branch and combine it history with the main branch

# Working with GitHub

Now it's time to create your remote repo where we you will be uploading your files locally.

`Note:-` Local repository (repo) means the repo which is on our system. Whereas remote repo means the one which is on other remote system/server, e.g. GitHub, GitLab, Bitbucket, etc.
## Push local repo to GitHub :-

To save and backup your project remotely on your GitHub account, copy and paste the link of your repo in the command below

$${\color{green}git remote add origin] [Remote Server Link] }$$

Once the changes have been pushed, your remote repository will be updated

If you are satisfied with the changes, you can push all the changes made using the following command

$${\color{green}git push [variable name] master }$$

This command sends the committed changes of master branch to your remote repository.
## git diff

$${\color{green}git diff}$$

This command shows the file differences which are not yet staged.

$${\color{green}git diff –staged}$$

This command shows the differences between the files in the staging area and the latest version present.

$${\color{green}git diff [first branch] [second branch]}$$

This command shows the differences between the two branches mentioned.

## git reset

$${\color{green}git reset [file]}$$

This command unstages the file, but it preserves the file contents.

$${\color{green}git reset [commit]}$$

This command undoes all the commits after the specified commit and preserves the changes locally.

The benefit of both of these commands is that you can use them to remove or edit changes you’ve made in the code in previous commits.
## git rm

$${\color{green}git rm [file] }$$

This command deletes the file from your working directory and stages the deletion.

## git pull

$${\color{green}git pull [Repository Link] }$$

This command fetches and merges changes on the remote server to your working directory.


That’s all for now. However, I will continue to update this sheet with new useful Git commands I will learn during my DevOps adventure.
