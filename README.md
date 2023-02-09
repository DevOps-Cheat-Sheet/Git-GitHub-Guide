# git-cheat-sheet

## Hello there, I am Otto, trying to make some code changes

`Git is the fundamentals to everyone planning to go into the field of DevOps and it is used for version control`

As a beginer, it is important to get your hands dirty with the git commands if you want to excel in this field.

I have summarized a bunched of them below to guide you.

Feel free to reach out to me incase you have any further challenges.

Git & GitHub has steadily risen from being just a preferred skill to a must-have skill for multiple job roles today. In this article, I will talk about the Top 20 Git Commands that you will be using frequently while you are working with Git.

Following are the Git commands which are being covered:

1. git config
2. git init
3. git clone
4. git add
5. git commit
6. git diff
7. git reset
8. git status
9. git rm
10. git log
11. git show
12. git tag
13. git branch
14. git checkout
15. git merge
16. git remote
17. git push
18. git pull
19. git stash.

So, let’s get started now!!

## git config

<span style="color:orange;">git config -global user.name “[name]”</span>

<span style="color:orange;">git config -global user.email “[email address]"</span>

This command sets the author name and email address respectively to be used with your commits.

## git clone

<span style="color:orange;">git clone [url]</span>

Used to create an instance of the remote repository into your local repo.

## git init


<span style ="color:orange;">git init [repository name]</span>

This command is used to initialise a new repository.

Once done, now you have a hidden subdirectory called `.git` in your project directory that contains all of your necessary repository files.

# Add Files and Commit changes

Select the files which you want to be attached to your git project and use the following command to add the files

<span style="color:orange;">git add [file]</span>

This command adds one or more files to the staging area

This command doesn't add `.gitignore` file by default

<span style="color:orange;">git add .</span>

This command adds all files to the staging area.

#### Then commit all the changes with a commit message using the command

<span style="color:orange;">git commit -m “[ Type in the commit message]” </span>

The first part of the command `git commit` tells Git that all the files staged are ready to be committed so it takes a perminent snapshot of the files. 

The second part `-m "first commit"` is the commit message.

<span style="color:orange;">git commit -a</span>

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

## Status Checking

To check the working tree status, file details, use the command

<span style="color:orange;">git status </span>

This command lists all the files that have to be committed.

# git push

If you are satisfied with the changes, you can push all the changes made using the following command

<span style="color:orange;">git push [variable name] master </span>

This command sends the committed changes of master branch to your remote repository.

<span style="color:orange;">git push -all [variable name] </span>

This command pushes all branches to your remote repository.

## git log

If you want to view the commit details then use the command

<span style="color:orange;">git log </span>

This command is used to list the version history for the current branch.

It will give you the result as the commit object, name of the author who made the changes, timestamp, and the changes.

# Remote backup repository

To save and backup your project remotely on your GitHub account, use the following command

<span style="color:orange;">git remote add [variable name] [Remote Server Link] </span>

This command is used to connect your local repository to the remote server.

Once the changes have been pushed, your remote repository will be updated

## git diff

<span style="color:orange;"> git diff</span>

This command shows the file differences which are not yet staged.

<span style="color:orange;">git diff –staged</span>

This command shows the differences between the files in the staging area and the latest version present.

<span style="color:orange;">git diff [first branch] [second branch]</span>

This command shows the differences between the two branches mentioned.

## git reset

<span style="color:orange;">git reset [file]</span>

This command unstages the file, but it preserves the file contents.

<span style="color:orange;">git reset [commit]</span>

This command undoes all the commits after the specified commit and preserves the changes locally.

## git rm
<span style="color:orange;">git rm [file] </span>

This command deletes the file from your working directory and stages the deletion.

## git branch

<span style="color:orange;">git branch</span>

This command lists all the local branches in the current repository.

<span style="color:orange;">git branch [branch name] </span>

This command creates a new branch.

<span style="color:orange;"> git merge [branch]</span>

Us to merge the branch and combine the specified branch’s history into the current branch

<span style="color:orange;">git branch -d [branch name] </span>

Used to deletes an existing branch.

## git checkout

<span style="color:orange;">git checkout [branch name] </span>

This command is used to switch from one branch to another.

<span style="color:orange;">git checkout -b [branch name]</span>

This command creates a new branch and also switches to it.

## git pull

<span style="color:orange;">git pull [Repository Link] </span>

This command fetches and merges changes on the remote server to your working directory.
<span style="color:orange;"></span>
