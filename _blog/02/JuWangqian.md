---
author: "Wangqian Ju"
title: "Git after an existing project"
layout: post
topic: "02"
short-topic: Happy git and GitHub
due-date: 2022-02-03
root: ../../
---

## Prompt:

git and Github are tools for helping with versioning of files in collaborative efforts as well as archiving entries for your future self. 
Unfortunately working with git isn't always completely straightforward. 
Jenny Bryan's book "Happy git and github with R" helps with that. The book is available from [http://happygitwithr.com/](http://happygitwithr.com/). Have a look over the index and pick one of the chapters for a more in-depth read.

Write a blog post answering the following questions: 

1. **Write a short (100-150 words) summary of the chapter you read in-depth.**

    The chapter I read was `17 Existing project, GitHub last`. It talks about how to connect a local existing R project to GitHub.
    
    If we already have an R project, the workflow is:
    -   make the project directory a Git repo
        -   `usethis::use_git()`
        -   `git init`
        
    -   stage and commit: clear this repo 
    
    -   make and connect a GitHub repo
        -   make sure that Git knows who we are: SSH or HTTPS has proper setup
        -   `usethis::use_github()` -> everything in one line
        -   Or, create the repo on GitHub (using the browser), then connect
            -   connect using RStudio: Git pane -> `Add remote`
            -   in the shell: 
            ```
            git remote add origin url/to/the/repo.git
            git push --set-upstream origin main
            ```
    -   confirm the repo on Git is updated with the local

2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

    I found this chapter interesting because I have some local projects and having them as Git repos would make life much easier, especially when one has multiple machines. And I believe having the ability to make any R project a Git repo would encourage me to write and share.


3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

    HTTPS vs SSH:
    
    I was using SSH since I knew Git. But it seems that the default setting that Jenny suggested is to use HTTPS instead of SSH. After checking `chapter 9 Personal access token for HTTPS`, what I found is that HTTPS is "easier to use". And if I get both HTTPS and SSH, I can have one repo for SSH and another repo for HTTPS.


