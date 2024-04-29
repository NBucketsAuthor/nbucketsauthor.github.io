---
title: How long does it take to write a novel?
layout: post
post-image: "/assets/images/blogpost_1_heatmap.png"
description:
tags:
- statistics
- visualization
- word count
---

Since Day 1 of my writing journey, I've been keeping track of the number of words I put down on 
paper each day. Reading around, I quickly realized that every author has their own pace.
Stephen King famously writes 2,500 words every single day -- no exceptions. Ernest Hemingway was 
content with finishing his day with a fifth of that. Consistency is key, but for me, accepting 
my own writing pace and limits helped me become more productive. Oh, right. Gave me fewer
burnouts, too.

In the beginning, I used a simple table which I manually updated. A piece of paper won't go a long
way if you plan to keep doing this, so any of the usual suspects (Google Sheets, Excel, 
LibreOffice, etc) will do. Recently I realized that the writing program which I use (Scrivener, 
not affiliated), automatically keeps track of this information. That was a fun moment, 
because I went back to my projects and began looking at the numbers. I knew how long each of my
books had taken me to write, but I didn't know exactly how many days I wrote for each book, or
how many words.

There's a common wisdom about word count when it comes to writing a book. Given that a novel has
about 90,000 words (depending on the genre), write 1,000 words per day and you've got yourself a 
first draft in as little as three months. Easy, right? If only. Here's a 
visualization of the days I actually wrote for my second book, *Break Even*. These include only
days in which I progress the manuscript and exclude days in which I edit, revise, and proofread.

<p align="center">
  <img src="/assets/images/blogpost_1_heatmap.png" alt="Visualization of daily word count for my second novel Break Even" style="width:600px">
</p>

Most of the days are gray, meaning I wrote exactly 0 words in these days. Zero. Zip. Nada.
There's also a nice accumulation of writing happening around holidays, where I have more time
than usual. So, how many days did I *actually* write on?

<p align="center">
  <img src="/assets/images/blogpost_1_distribution.png" alt="Distribution of daily word count for Break Even" style="width:600px">
</p>

97 days. With an average of 857 words per day, it took me exactly 97 days to type THE END in
my second novel. Of course I'm talking about a first draft which has to be improved, but hey,
this is what rewrites are for. The number 97 is strikingly close to the rule of thumb of 90 days.

The second thing the data shows me is the average number of words I write when I manage to write.
My daily average is about 850 words, and that's what I feel comfortable with. Sure, I'll have
good days where I crunch a couple of thousand words, but also days where I'll struggle to 
come up with just a few hundred. The pattern I've noticed is the following though: a high day will
usually lead to a break the day after, while a low day not.

### Okay, what now?
I found that paying attention to the statistics of my daily word count helped my productivity.
I also found it fun to watch at.
Since I love data and visualization, I made this interactive app so that other writers can
explore their own statistics, learn something from the data, or just have fun plotting it.

### Where?
The app is <a href="https://nickbuckets.shinyapps.io/word_count/">here</a>, and it looks like this:

<p align="center">
  <img src="/assets/images/blogpost_1_viz_daily_word_count.png" alt="Interactive shiny app to visualize daily word count statistics" style="width:400px">
</p>

In case you want, you'll be able to upload your own data and visualize it, as well as change the 
colors etc.

Enjoy!
