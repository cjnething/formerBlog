---
layout: post
title: "Getting Started with Git and GitHub"
date: 2015-07-15
---

When I was first getting started with Git and GitHub, I had a lot of questions. After using Git/GitHub regularly over the past six months, I have a much better understanding of these tools and would love to pass that information along. If you are also trying to learn about Git and GitHub through blog posts and similar tutorials, hopefully this blog post will answer some questions that you have.


# What is Git? 
First things first: Git is a language that is used in the command line (also known as the terminal).

According to the Git website, Git is a free and open source distributed version control system for programming projects. If you are like I was a few months ago, that means very little. Another way to look at Git is that Git is kind of like an advanced version of saving documents. If you wanted to save a report that you had written, you would just click "save" and give your report a name in your documents folder. Very similarly, you would use Git to to save your programming files. So instead of clicking on buttons that do what you want, you would type in Git commands that would accomplish a very similar goal.


# What are the benefits of Git?
- Save changes
- Revert to previous changes if you make a mistake
- Save all projects to "the cloud"
- View all versions and complete history of a project
- Multiple users can contribue to the same project


# What is GitHub?
GitHub is a website that hosts git repositories (more on repositories later). Git and GitHub are **separate** - you can sue Git without using GitHub (there are other websites such as GitLab, but GitHub is the most popular such site).

GitHub takes all of the features of Git and adds new features: 
- Web interface
- Access control
- Wikis
- Feature requests


# Important Terms
- **Terminal/command line**: a tool which allows you to type text commands to perform specific tasks instead of using the mouse to point and click on menus and buttons
- **Repository (repo)**: where the history of your work is stored
- **Clone**: a copy of a repository (i.e. clone GitHub repository to your local computer)
- **Fork**: your own copy of someone else's repository, where you would make diverging changes
- **Branch** : essentially a fork of your own repository; allows you to work on multiple features at once without fear of affecting your working master branch
- **Commit**: each "hard save" of your work; a repository shows the history of all commits

# Navigating the Terminal
- Use the terminal to navigate the tree structure of files
- **pwd**: Prsent Working Directory (displays wher eyou are currently located)
- **ls**: List current directory contents
- **cd**: Change Directory (move to a new location)
  # Ex. **cd algorithms**: changes to the algorithms folder
  # Ex. **cd ..**: changes to parent directory (".." moves to the parent) 
- **open**: Open file in Finder
  # Ex. **open coderbyte**: while in parent directory of coderbyte, opens the coderbyte file
  # Ex. **open .**: while in the file you want to open, opens that file

# Getting Started with Git

Install Git for the first time
: **git**

Configure environment so your git commits have your name
: **git config --global user.name "Julia Nething"**

Configure environment so your git commits have your email
: **git config --global user.email cjnething@gmail.com**

Create a local version of a repository on GitHub
: **git clone https://github.com/cjnething/project-euler.git**


# How to create a repository on GitHub
1. Go to your GitHub profile page
2. At the top of the page, click "+" to create new repository (Initialize: Yes)
3. In order to clone it to your local machine, click on "Copy to Clipboard" on the right-hand panel
4. In the Terminal: **git clone** (+ URL in clipboard)
5. In the Terminal: **open .**
6. In Finder, drag the folder of your new repository to your Sublime or other text editor
7. Right-click repository name to add new file
8. Make a change to the file (add a comment or something) and save (command + S)

# Using Git
Now that you have a repository and you have made a change to the repository that you would like to save to GitHub, here are the steps that you will need to complete.

1. Check what has changed
: **git status**
2. Add the changed files to the "staging area" to be committed
: **git add .**
3. Create a commit
: **git commit**
4. Write the commit message, then hit "ESC", then type in ":wq" (Write Quit)
: **(commit message, esc, :wq)***
: Example of a commit message: "Add a helper function that checks if a number is prime"
: Commit messages help you remember what you accomplished and when so you can see the full history of your project
5. Pushes commits to your GitHub
: **git push origin master**


# Further Resources
- Pro Git: http://git-scm.com/book/en/v2 
- Git Immersion: http://gitimmersion.com/ 
- YouTube Git: https://www.youtube.com/user/GitHubGuides/featured 
- Think Like a Git: http://think-like-a-git.net/sections/about-this-site.html
- Code School’s Try Git: https://www.codeschool.com/courses/try-git (Basic course is free, further courses require a subscription)


This was just an introduction to Git and GitHub, and hopefully it was useful to you. If you have any questions, or if you have any tips for me, please leave a comment or send me an email at cjnething@gmail.com!
