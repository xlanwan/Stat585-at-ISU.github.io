---
layout: blog
topic: "01"
short-topic: Asking Good Questions
due-date: 2022-01-27
root: ../../
---

## Prompt:

Asking good questions is a valuable skill to have - asking questions in an online setting is both easier and harder than asking questions in person: we can prepare to ask a question but we are also expected to prepare.
The links posted here give some advice on how to ask good questions:

- stackoverflow's [Asking a good question](http://stackoverflow.com/help/how-to-ask)

- R's [Posting guidelines](https://www.r-project.org/posting-guide.html)

- [minimal complete verifiable example](https://stackoverflow.com/help/mcve), [minimal reproducible example](https://www.tidyverse.org/help/)

Follow these links and read through the advice given, then

1. **Pick at least one question from stackoverflow or the R help and answer it.**

Write a blog post answering the following questions: 

2. **Document which question you answered (link to your answer).**

Question: How to make sure the geom_text graph labels stays at the right place?

Link: https://stackoverflow.com/a/70885243/18050151

I recommend to use `geom_text()` instead of `geom_text_repel()`. Here is my code: 
```
geom_text(aes(label = ..count..), 
position=position_dodge(width=0.9),      # move to center of bars
vjust = -.25     # nudge above top of bar
).
```

I recomend you build up a summary table first, then draw the graph. It could help you add other labels easily, such as percentage. Here is my code:
```
withSalary %>%
  group_by(Mjob, as.factor(salary_range)) %>%
  summarize(count = n(), .groups = "drop_last") %>%
  mutate(freq = count / sum(count)) %>%                                         # a summary table include count and pct.
  ggplot(aes(x = Mjob, y = count,fill=as.factor(salary_range))) + 
  geom_bar(stat = "identity", position = "dodge") +
  geom_text(aes(label=sprintf('%d (%s)', count,scales::percent(round(freq,1)))), 
  position=position_dodge(width=0.9), vjust = -.25) +                           # the label include count and pct
  ggtitle("Applicants' salary group by their mothers' jobs") +
  labs(fill="Mothers' jobs")
```

3. **Relate your experience of answering the question to your reading. **

Based on the reading of Minimal Reproducible Example, I use the simialr data to write a code and draw the bar to get the right answer. Then I point out the advised part,and do the correction. For this part, I keep my code simple and reproducible. I also gave another code to improve the original one and give the annotation. Based on the reading, I keep my code minimal, complete, readable and reproducible. 


<!--Go to [https://github.com/Stat585-at-ISU/blog](https://github.com/Stat585-at-ISU/blog) for instructions about how to prepare and submit your blog post.-->
Instructions to follow.


{% assign num_posts = site.blog | size %}
{% if num_posts > 0 %}
## Class posts:

<ul>
{% for post in site.blog %}
  {% if page.topic == post.topic %}
  <li><a href="{{ post.url }}">{{ post.title }} by {{ post.author }}</a></li>
  {% endif %}
{% endfor %}
</ul>
{% endif %}
