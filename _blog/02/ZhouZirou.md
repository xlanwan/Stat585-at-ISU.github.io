---
layout: post
author: "Zirou Zhou"
Title: "Blog 2"
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

I read throgh the chapter 9 about the Personal access token for using the git in Rstudio. Jenny explained detailly about why using PAT and contacting github through the https is recomended. As the HTTPS with PAC can operate the Github API within the Rstudio by *usethis* Packageand. And PAT will also be used in REST API which my be not important now but will be useful later. And she represents 2 ways about how to generate the PAT, either by using the github or using the Rstudio *usethis* package, and notified the importance about the PAT and the ways to storegrage it safely. And other than storage PAT in password apps, The R package *gitcreds* and *credentials*. Finally Jenny shows how to re token the PAT after it got expired and solved some common questions when using PAT on MAC, Windows or Linux git.

2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

I downloaded the origional Lab-1-team-1 from github and made some changes, and I pull again after Bufei emiled me she had made some changes. And this result in bazzrd in the Readme.rmd and I lost some part of my work. If I read the Chapter 28 before doing this, I think it can be avoid.

3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

I learned how to pull and push the changes from Rstudio to the Github without making bazzrd and how to use the commit in Rstudio.
