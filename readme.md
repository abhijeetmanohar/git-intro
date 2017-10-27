# Git guide

This repository is a guide for people new to open-source community and version control softwares like git, cvs etc.

## Some common terms

Here are some of the terms you will encounter frequently while working with git.

* **Repository** - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation). 

* **Fork** - A fork is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original. Forks remain attached to the original, allowing you to submit a pull request to the original's author to update with your changes.

* **Clone** - A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. With your clone you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online.

* **Issue** - Issues are suggested improvements, tasks or questions related to the repository. Issues can be created by anyone and are moderated by repository collaborators.

* **Commit** - A commit, or "revision", is an individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID that allows you to keep record of what changes were made when and by who. Commits usually contain a commit message which is a brief description of what changes were made.

* **Pull request (PR)** - Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators.

* **Branch** - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

## Installing git to on your machine and setting everything up.

git is a command line tool that allows you to work with version control systems.

### Installing
* **Mac** - To install git on a Mac follow [this link](https://git-scm.com/download/mac).
* **Linux** - To install git on a Linux machine follow [this link](https://git-scm.com/download/linux).
* **Windows** - To install git on a windows machine follow [this link](https://git-scm.com/download/win).

### Setting you environment
You need to set your `username` and `email` before you proceed. Make sure these are same as that of your GitHub account. I will be using my username `m-murad` and email `murad.kuka@gmail.com` for this example.
* **Setting your username** - 
`git config --global user.name "m-murad"`
* **Setting your email** - 
`git config --global user.email "murad.kuka@gmail.com"`

## Forking a project
Before you start working on a project you need to create your own copy of the repository. In other words you nedd to fork the project or repository. This can be done by click the Fork button on the top right corner of the project GitHub page.

TODO: Add an image here.

This will create a copy of the project which belongs to you i.e. you will be owner of that copy.

## Setting up the project locally.
Once You have forked a project, its time to clone the project i.e. make a local copy of the project. This is done by git clone command which goes like this.

`git clone URL_OF_THE_PROJECT`

for my copy of the project link would be 

`git clone https://github.com/m-murad/git-intro`

for you the link will be different. It will have your username. The URL is of the format 

`https://github.com/YOUR-USER-NAME/git-intro`

Once the project is cloned you can run or edit the project locally in an IDE of your choice.

## Creating a branch.
The purpose of branches is to enable you to work on different features/issues simultaneously. By default you are in the `master` branch. 
To create and checkout (Jump to that branch) a branch name `branch2` we use the command

`git checkout -b branch2`

To checkout to an existing branch like `master` we will use the command 

`git checkout master`

It is always recommended to use meaning full branch names. eg is you are working to fix or add transparency the name of the branch should be `transparency` or something similar.

## Setting an upstream

## Creating an issue and pull requesr
