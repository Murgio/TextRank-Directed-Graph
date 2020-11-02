# Unsupervised Graph-Based Ranking Model for Tech Talk Summarization

<img src="https://i.imgur.com/KdBhz4c.png" width="425"/> <img src="https://i.imgur.com/6rYOPA2.jpeg" width="425"/>

## Introduction
Staying relevant in the ever changing technology landscape can be a challenge. At work, we are expected to keep abreast of new computer technologies, web design feels like a constant game of catch up and quitting the race for only a few months months will result in your skill set becoming obsolete.

In short, we can see how knowledge gradually becomes its own unique and important form of currency at a fundamental level. Common resources for developers to brush up their skills include books, podcasts, blog posts, trending GitHub repos, and YouTube videos.

With hundreds of tech talks shared daily, YouTube won in recent years popularity amongst developers - being more commonly their first choice to inform themselves about current technologies. Unfortunately, more often than not these type of videos challenge us to allocate a great chunk of time from our daily life. Expected video lenght range from 20 minutes up to 3 hours, with a busy working schedule we simply put don't have time to watch YouTube videos.

In a recent thread, a Hacker News user wrote:

>*Time management, to me, is a more powerful “skill up” than anything that could keep your GitHub green. When you know you have limited hours in the day and you have hard time commitments, you have no choice but to learn and work efficiently.*

Browsing myself Hacker News for nearly six years, one topic wich regularly shows up is **staying up to date** (Figure 1). Users indicate that they have no time for almost anything besides their day-to-day job.
With methods known from natural language processing, is it possible to densify the content from a YouTube video into one comprehensible PDF file?
<p align="center">
  <img src="https://i.imgur.com/T4ZaB1N.png" alt="hackernews" width="70%"></img>
</p>
<center>Figure 1: Recent threads on Hacker News</center>

# Goal
YouTube videos provide us with auto-generated subtitles. In the jupyter notebook we aim to develop a model to extract useful bits of knowledge from subtitles and provide the user with a PDF file containing the summary.
