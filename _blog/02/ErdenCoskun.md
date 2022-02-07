---
Author: Coskun Erden
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
I read chapter 15 in depth to understand how I can create a new github project and work on it through RStudio. Bryan suggest GitHub first then RStudio approach as this method sets up the local Git repository for immediate pulling and pushing. In Github first approach, apparent from its name, we create a repository in Github first. Although creating repository process is explained in chapter 11 previously, Bryan explains it once more and explains how we clone the repository to our local computer by using RStudio. First we copy the HTTPS URL in Github. Then we start the RStudio and create a new project by following the path File > New Project > Version Control > Git.  We paste the URL of the Github repository by determining the project folder carefully. We can make changes in already existing files, e.g. Read.md , or in new ones we created , e.g. RMarkdown. We commit these changes to our local repo by clicking the Git tap, checking Staged box for any files we want to commit and then clicking commit. We can also use Diff option to see details about what has changed in the file since the last commit. Committing saves the changes in the local repo. We use “Push” button to send our local changes to GitHub repository. Bryan emphasize that pulling those changes in before we attempt to push is a good habit.


2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

I have not experienced a big problem in any team project I involved in. But, I shared my R files with teammates through e-mail or drive. I had to wait for their responses and modify the codes based on their feedback. I believe that git would be really helpful in communicating with teammates. We could communicate more efficiently and finish the projects in a shorter time.  
 

3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

I learned about "branches" from Bryan's book. I found it very beneficial not only in collaborating with others but also in personal work. As Bryan states it can be used to experiment new ideas without jeopardizing the state of the main product.
