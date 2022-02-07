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

I read Chapter 29: **Time Travel: see the past**. This chapter mainly talks about how we can access past commitments in the github repo. It turns out that we can visit any arbitrary adjustment we made on a file, by simply clicking the "commits" botton at the top of the repo. We can also share different versions of a specific file with others. A more detailed version check for a single file can be found in "blame" and "history", where we can see modifications of each version from previous ones. Therefore we can also point others directly to a specific location where we have make certain changes, which is super useful. If we are interested in modifications of specific places in a github file, for instance modification in section "introduction" for a manuscript, we can simply use the search box to direct us there.

3. **Looking back at all of the team projects you have been involved in, describe the biggest mishap you had. Could that have been avoided using git? How?**. 

This is truely helpful for me, especially for revisiting or reboosting code. For my first research project, all R code I wrote was stored locally. I realized that sometimes when I make a change to the algorithm, it may went into errors in sumulation. It could happen right after I made the change, or it could happen months later when I ran another set of simulations, which I had no idea what I have done a month ago. Another problem is that, my advisor had no idea what I have done to the code.

What I did was to save the code file every time before I make a major change, marked with the date of the change. This is super tedious, and if I want to find where has gone wrong I had to compare the code between different versions line by line. These can all be settled easily by github, I will also recommend my advisor to use it from now on. 

5. **Give an example of one new git feature that you learned about from Jenny Bryan's book.**.

fork and clone: put a copy of other people's github repo into your own. 
