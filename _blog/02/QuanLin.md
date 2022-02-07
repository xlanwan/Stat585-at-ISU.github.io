---
title:  "Happy git and GitHub"
author: Lin Quan
layout: blog
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

Chapter 15 describes how to create a new project from GitHub and connect it to Rstudio. The basic rule follows "GitHub first, then Rstudio" sequence. First, We make a repo on GitHub (/GitLab/Bitbucket). We can choose repository template, name, description, public/private and initialize it with a REAMNE file. Then we copy a clone URL. Second, we make a new RStudio project via git clone. We use the copied clone URL to open the new project in RStudio. In RStudio, we see the `README.md` file we created in GitHub. At last, we make local changes and push them to GitHub. After every change from RStudio, we can save and commit it. Then we push our changes to GitHub. In GitHub, we can see the changes from RStudio and confirm the local change propagated to the GitHub remote.

2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

For all previous team projects, we always met in person and worked on projects together. The reason is that we don't know how to see others' updates. By using git, this problem can be solved easily. Git is a version control system. We can make local changes on our computers and push them to GitHub. Others in the team can see the changes immediately. Git helps us be more productive. 

3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

If the password from GitHub is not a acceptable credential when connecting RStudio to Git and GitHub, a personal access token (PAT) can be used. In R, you do `usethis::create_github_token()` to generate PAT and copy it. Then you call `gitcreds::gitcreds_set()` and paste the PAT. Then you should be able to connect to GitHub. 









