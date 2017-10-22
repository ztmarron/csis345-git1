---
layout: page
title: Git Assignment 1
permalink: git/assignment1
---

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

* 
<add an instruction thing for how to commit:
Make changes to your files.
Git status to see if the file shows as changed.
Git diff to check the changes
Git add <filename> to add the file’s changes to the index.
Git status to make sure the changes are added.
Git diff should no longer show the changes.
Git diff --cached should show the changes you added.
Git commit should prompt for a message with the editor
Git status to see that things are clean
Git log to see that your commit is added to the index.
>

Write your answer to the first question, then commit it up.
Write your answer to the second question, then commit it up.
Write your answer to the third question, then commit it up.

<will we use github or gitlab?? I’m preferring github…>
Now that you have your questions committed, create a github account (if you don’t have one already); create a repo, and follow the instructions to push up an existing project.

Copy the url to your repository in the browser and send it to my email -> ryan+git2017@sharptop.io
This assignment is worth 10 points and is due by the start of class on Wednesday.



