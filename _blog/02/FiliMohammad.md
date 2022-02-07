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

    __Answer__: 
    
    I picked chapter 29 which is about how to go back to previous version and see the contents in a standard way. To do so, we can use t he git commands; however, it is mentioned that this is not straightforward. Instead, we can use the github's hyperlink. By going to the github repo, we can see the history of commits and also the differences from one document to the other. For each commit, we can go and click on the `< >` part, and the we can use the URL for that webpage and work on it.
    Another interesting info can be found on the blame view, where we can see who is the last one editing each line, when was that done, and what was the commit message for that. We can also go to the previous version of a specific part by clicking the "Stacked Triangle" in blame view.
    There is another view mode called "history", which contains all commit info. We can even specify certain lines out of a file to discuss with other teammates.
    

2. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

    __Answer__:
    
    I was collaborating on a project which needed coding. After a while and working on different scripts, I made a couple of significant changes on a copy of the codes on a remote machine, while I had the old version on my computer. One day, I wanted to update all the codes on the remote machine with the codes on my machine. I copied all the scripts from my PC, and patsed into the remote machine, but later on, I found out that I had overwritten the most recent codes which where in the remote machine.
    If I had used git, I could have an integrate environment regardless of the machine that I am using, and also go back and forth with the versions if needed.

3. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

    __Answer__:
    
    I learned about the blame and history view which I think are really useful to see who was the last one editing a particular section, and go to that version if needed. Also, thsi makes it a lot easier to go back and see how things were at a certain time, and how it was changed.
