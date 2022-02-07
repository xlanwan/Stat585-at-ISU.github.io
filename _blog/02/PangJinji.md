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

The chapter I read in-depth is Early GitHub Wins. I learned whenever I want to start a new project, the best case will be first create a git repo for the new project, then create a R project which is linked to that repo.Besides, I also learned how to make existing project connect to GitHub,there are two ways, either repeat "New project, git first" then add the existing project to the new project, or in the current project, making it a R Studio project by `File > New Project > Existing Directory `.
I started using GitHub since last spring but I still have many existing projects that are not on GitHub. After reading this book, I am sure I will link some my projects to GitHub gradually. 



2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

Answer: 
Some of the courses I have taken here at ISU use group project as final exam. I remembered for one group project, we spent quite a time combining different person's work into a pdf file. Though we were all using Rmd.file to write our solutions in that time, but each person has their own layout setting preference. Also, we didn't use git to communicate, instead we just sending file through Zoom chatting windows, that was a disaster. 
It would have been avoied if we used git. First, we just need to upload an agreed template before everyone starts using their own templates. Second, using git makes downloading and updating files easier to everybody.



3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

I learned that `git pull --rebase` can create a nicer history than `git pull` when integrating local and remote commits. It avoids a merge commit, so the history is less cluttered and is linear.





