---
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

I read chapter 9, "personal access token(PAT) for HTTPS". This chapter introduces the reason that PAT being used, which is passward is not an acceptable
credential when talking to Github as a Git server, and how to generate/store token using R. It compares different ways to working with Git/GitHub, i.e., HTTPS and
SSH, and their differences. The author strongly suggested using HTTPS, as it is easier to use and more friendly with the beginners. Last, it talks about some common 
problems, such as PAT is store valid but later being invalid/PAT doesn't persists in macOS/Windows/Linux, that people might run into when using HTTPS PAT and their 
solutions.

3. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

We have to email each teammates updates back and forth. Sometimes people get confused and forgot to get the newest updates from someone involved in the final 
result. By using git we can push and pull our updates as well as keep tracking on which part we have changed. It will be easier to collaborate using Git.

5. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

I learned how to connect git with Rstudio. I first tried to connect using SSH but it won't work, then I switch to HTTPS. I don't know that password is not 
acceptable credential as a Git server until I go through chapter 9 and using PAT instead. Finally I managed to connect my lab repository to Rstudio.
