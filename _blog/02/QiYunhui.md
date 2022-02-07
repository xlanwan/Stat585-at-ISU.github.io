---
title: "Blog 2"
layout: post
author: Yunhui Qi
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

I read Chapter Git fundamentals.

It mainly talks about the some basic concept of Git. **Repository** is a set of files whose evolution is managed by Git. **Commit** takes a snapshot of all the files in repository. **Diff** records the difference between any version and the original version, indexed by **SHA** or user defined tag. We can check **history** to see the commit message.

It also introduces some git commands(using in the terminal), including clone, remote, add, commit, status, log, diff, push, pull, fetch, checkout branch and so on 

Branches allows team members to work separately without overwriting each others work. Use **git branch** and **git checkout** to create and close a branch, work on the branch and merge the branch to the main using **git merge**. If both the branches change the same part of the same file, a merge conflict appears, change them to one version and use **git add**, **git commit** to finalize  the merge. Use **git merge --abort** to abort the merge and go back to the state prior to merge

Remote repo is the version of the project on the internet. Use **git remote -v** to get URLs of all the remotes. use **git remote add Nickname URL** to add a new remote (git clone can also do), use **git fetch** to get data from the remote. One can also push to or pull from the remote repo.


2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

I used to work in a team with three members on a project called Yelp Data Analysis, the repository is https://github.com/YunhuiQi/Stat628-Module2.git . At that time, we did not know how to use branched. Actually we even did not use commands like git clone, push or pull. We directly downloaded the older version and uploaded our own new version. This often made us confusing, and it took us a lot of time to track the difference and make the version up to date. After reading this chapter, I believe the branch feature will help in our team work. We can work on our own branches and merge them all finally, the confilts will tell us what's wrong. The team work will be more clear using git branch.


3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

Git branch.

-create my own branch: git branch YQ

-merge this branch to main: git checkout YQ; git merge YQ

-if conflicts: git status

