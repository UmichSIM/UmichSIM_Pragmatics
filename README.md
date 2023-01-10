# UmichSIM_Pragmatics
Place to learn how to better cooperate for coding tasks.

## Introduction
This repo contains tutorials on some basic tools that you will use intensively in our project. The name comes from [EECS201](https://www.eecs.umich.edu/courses/eecs201/wn2022/), which contains a more comprehensive version of these tutorials (highly recommend taking this course).

## Shells
### Obtaining a Unix Shell
#### Windows
Natively, Windows use another type of shell called CMD/PowerShell. Fortunately, with the help of Windows Subsystem for Linux (WSL), it's easy to access a linux shell within the subsystem. Check [this link](https://learn.microsoft.com/en-us/windows/wsl/install) to install WSL.

#### macOS&Linux
Belonging to the family of "Unix Like" operating systems, macOS and Linux supports Unix Shell natively. Just open a terminal software (like Terminal.app on MacOS) and you are ready to go.

### first to remember
+ basic shell command structure
![image](https://user-images.githubusercontent.com/55869557/211469435-e5d546e7-6714-41c8-8670-3d13bf1e197d.png)
+ [TAB] - the most important key you need
  + helps complete your unfinished command or path
  + can even list available candidates

### Surfing in the file system
+ `pwd`
  + print working directory associated with your shell session
+ `cd`
  + change directory
  + usage: `cd /place/you/want`
  + `cd ..` will take you to the parent directory
+ `ls`
  + list contents in current directory
  + some options:
    + `-l`: display in list format
    + `-a`: also show hidden files (file start with `.`)

### Other useful commands and keys
+ `man`: see manual for commands
+ `ctrl`+`r`: search command history in bash
+ `ctrl`+`l`: `clear` the screen
+ `ctrl`+`d`: send EOF, can be used to close the current shell program


## Gitting Started
### Installation
+ Windows(WSL)
  + inside WSL, run `sudo apt install git`
+ macOS
  + install [homebrew](https://brew.sh/), a package manager for macOS
  + run `brew install git`
+ Linux
  + use your package manager

### Files status in git
![image](https://user-images.githubusercontent.com/55869557/211577924-1324b8b3-3be7-4561-9daa-a69825789677.png)

### Basic commands
+ `git init`: initialize git repo
+ `git status`: check repo status
+ `git log`: show log
+ `git add`: stage files
+ `git checkout`: change location of `HEAD`
+ `git commit`: commit staged changes
  + make sure your commit message is meaningful!
![image](https://user-images.githubusercontent.com/55869557/211599023-888fa7f1-975b-4640-8c8a-7a914aa2b0af.png)

### Branching
+ `git branch`: show branches
+ `git branch <branch-name>`: create a new branch
+ `git checkout <branch-name>`: switch to another branch

### Remotes
+ `git clone <URL>`: clone from a remote repo
+ `git remote -v`: will list your remotes
+ `git pull`: pull from remote for new changes
+ `git push`: send commits to the remote


## Github
### Issues
[Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) let you track your work on GitHub, where development happens. I'll introduce some useful components in an issue.

+ Assignees - assign the task to someone!

![image](https://user-images.githubusercontent.com/55869557/211592971-d364d4c8-1476-4a89-9aea-e37063481534.png)

+ Labels - define your task!

![image](https://user-images.githubusercontent.com/55869557/211592793-181ad927-1756-4a7a-ad7f-888690962b0f.png)

+ Development - Link your working branch to the issue!

![image](https://user-images.githubusercontent.com/55869557/211593068-25f30f40-bf05-412a-9552-bbcc40b613c0.png)

+ issue link - refer to other issues/PRs here!

![image](https://user-images.githubusercontent.com/55869557/211595194-e0a987ef-5bd3-4728-87e2-0d0264bc0e77.png)

### Pull Requests


### Do it yourself!
+ create an issue called `first issue - [your name]` in this repo
+ refer your issue in [Master issue list](https://github.com/UmichSIM/UmichSIM_Pragmatics/issues/1)
+ create a new branch in the `Development` tab
+ in your branch, add your name (and perhaps a link) in the [Who finished this tutorial?](#who-finished-this-tutorial) section.
+ add, commit, push
+ create a pull request for your branch to merge into main branch



## Useful Links
+ [EECS201 - Winter 2022](https://www.eecs.umich.edu/courses/eecs201/wn2022/) (better slides)
+ [EECS201 - Fall 2022](https://www.eecs.umich.edu/courses/eecs201/fa2022/schedule) (better short videos)

## Who finished this tutorial?
