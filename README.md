# Git Assignment 1

This assignment will review what we've learned on day 1 of git. To complete the assignment, you will need to get git set up, and perform some of the tasks that were taught in class. The actual assignment should be fairly simple. Getting git set up should be very simple for those of you on linux or a mac. If you're on Windows, it's not impossible, but it is a little more challenging.

# Install git on your system
If you don't want to bother with this, just use the linux server. However, using git will make your life as a CS student better, so taking the time to install it on your system will be worth it.

If you don't already have git installed, head on over to [the git downloads page](https://git-scm.com/downloads) and follow the instructions for your OS.

# Configure git
Use the following commands to configure your identity on git. This makes sure your commits have the right name. 

    $ git config --global user.name "John Doe"
    $ git config --global user.email johndoe@example.com

If you'd like to configure more options (like using vim as your default editor), head to the [First Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) page in the git docs.

# Create a github account
Go to [github](https://github.com/) and create an account. 

If you have time and feel confident, configuring an ssh key will save having to type your git password every time you push up a repo. It won't make a huge difference for this assignment, though, so it's not necessary to spend time on it now.

# Clone the assignment repository
Clone down the assignment repository

    $ git clone https://github.com/slackboxster/git-assignment-1.git

# Assignment
Answer the questions in `quiz.md`. Answer each question in a separate commit. Follow the steps below for each commit.

* Make changes to your files.
* see if the file change is detected with `git status`.
* see if the correct changes are detected with `git diff`.
* stage the changes with `git add <filename>`.
* check that the add did what you expected with `git status`.
* check `git diff` again to make sure it no longer shows changes.
* check `git diff --cached` to show the changes you've staged.
* make the commit with `git commit`.
    * Write a meaningful commit message (e.g. "Answers question 1").
* check that your working directory is clean with `git status`.
* check that your commit succeeded as expected with `git log` (you should see your latest commit message on top).

# Push your code up to a github repository.
Before you push up your code to your new repository, you will need to remove the reference to my repository with:

    $ git remote rm origin

Confirm that `git remote -v` produces no output.

In your github account, create a new repository. Follow the instructions to "push an existing repository from the command line".

Copy the url to your repository in the browser and send it to my email -> ryan+git2017@sharptop.io. Carbon Copy Dr Shaneck on the email too.

This assignment is worth 10 points and is due by the start of class on Wednesday.
