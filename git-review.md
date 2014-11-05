## Review Git Basics

#### Please complete the below material and submit to exercises in [students.gschool.it](https://students.gschool.it/)

#### A great reference for material is the [Git Book](http://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

#### Within this file, for each item below:

* Fill in the git command that performs the action
* stage the file
* commit the file
* push to github

##### This means you should have 14 commits and pushes for this exercise when you're done.

#### Get started!

* Display your working directory
  * git status

* Initialize a git repository in a newly created local directory
  * git init

* Display the status of a repository
  * git status

* Identify if files are staged or not
  * git status

* Add a file to the staging area
  * git add <file name>

* Commit the contents of the staging area using the -m flag
  * git commit -m "commit msg"

* Commit using the -m flag with a multi-line description
  * git commit -m "commit msg"

* Push your local repository to github (assume your remote is already set)
  * git push origin master

* Add a remote to your repository
  * git remote add

* Change an existing remote
  * git remote set-url

* Pull changes from a shared github repo to your local repo
  * git clone

* Show the history of a git repository
  * < your answer here >

* Show a log of your commit history
  * < your answer here >

* Roll back to a specific commit in history
  * < your answer here >

#### You should understand the following:

* Git stores the differences not versions of whole files - it is a history
* How --hard differs from not using --hard
* Why using --hard should be used with care
* How undoing, discarding or changing commits affects code that has been pushed
to a different remote
