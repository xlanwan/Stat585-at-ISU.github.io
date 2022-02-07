---
author: "Saqlain Ali"
title: "Repo, commit, diff, tag"
layout: post
topic: "02"
short-topic: Happy git and GitHub
due-date: 2022-02-03
root: ../../
output: github_document
---

## Prompt:

git and Github are tools for helping with versioning of files in collaborative efforts as well as archiving entries for your future self. 
Unfortunately working with git isn't always completely straightforward. 
Jenny Bryan's book "Happy git and github with R" helps with that. The book is available from [http://happygitwithr.com/](http://happygitwithr.com/). Have a look over the index and pick one of the chapters for a more in-depth read.

Write a blog post answering the following questions: 

1. **Write a short (100-150 words) summary of the chapter you read in-depth.**

Git is a version control system which helps groups of developers work collaboratively on projects. A repository or ‘repo’ is just a directory of files that Git   manages holistically. A ‘commit’ functions like a snapshot of all the files in the repo. Let us assume that version A was part of one Git commit and version B was part of the next commit. The set of differences between A and B is called a ‘diff’. Every time we make a commit, we should also write a short commit message. When you revisit a project to see recent changes by reading commit messages one can understand what changes had been made. Every commit needs some sort of nickname to be identified later. Git does this automatically, assigning each commit what is called a SHA, a seemingly random string of 40 letters and numbers. User can also designate certain snapshots as special with a ‘tag’, which is a name of their choosing.

2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**.

While working on a project in python named 'WC Analyzer' I found out that using git I could have efficiently make the changes to the code and push to Github repository. I was using Heroku platform(a cloud based platform for hosting) to deploy my web-app and it was connected to my Github repo manually. In order to make the necessary changes in the code and rerun the application I had to make another Github repo with the updated code and again had to connect to the cloud based platform which is a lot of work and totally inefficient. Instead, I should have connected the account of Heroku to git and could have easily made the changes to my code the push it to Github which then would be able to run the app properly.

3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

We can compare versions using the following git command in our terminal:
git diff
