---
title: New Year, New Blog
date: 2022-01-01
categories: [Ideas]
tags: [data-science, social-justice]
---

## Why am I doing this?
This is my first post on this blog and I wanted to start by trying
to articulate my reasons for creating this blog and then do a little
brainstorming about what kind of content I want to share here. I'm
sure things will change as I continue to work on this and what I
actually end up doing may look very different, but I have start
somewhere.

As a data scientist, I am very concerned about how big data and machine
learning are used to reinforce institutional and interpersonal oppression.
Algorithms written by people like me are making decisions that control
who should or shouldn't be approved for loans and credit cards, what
content to recommend to bigots, what posts should be flagged for
inappropriate content, and so much more. I want to find ways that this
same technology could be used to fight oppression rather than uphold it.

This is something I've been thinking about for a while and I have a lot
of ideas, some small, some big, on ways to use data for good. My goal
for the new year is to start actually trying to explore these ideas and
share my journey here. I am interested in any sort of social justice
related issues, but I will probably start with trans stuff because, well,
I'm trans.

## Brainstorming

### Studying the spread of transphobic ideas
This is probably the most ambitious project I've been thinking of. I would
want to study how transphobic ideas spread from institutions, in the form
of academic research and news articles, to the general public. The idea would
be to start with something like rapid onset gender dysphoria, look at the various
articles have been published about it, and then look at things like tweets
and reddit posts referencing those articles. The text from all of these can be
scraped and analyzed to get some sense of the impact transphobic articles have
on the online discourse.

### Making information on trans healthcare more accessible
While there have been a lot of advances in trans healthcare in recent years,
there is still not enough research being done on the subject and the research
that is being done is not widely known in the medical community. Because of
this, trans people often have to do their own research in order to make informed
decisions about their healthcare. In my day job I scrape data from medical
research papers to create a knowledge base centered around cancer treatments.
I would like to try to do something similar for trans healthcare research, but
with a focus on generating easy to read summaries of the key findings of the 
research so that trans people don't have to wade through pages of medical jargon
to understand it.

### Why *is* breadtube so white?
Many people have pointed out that the vast majority of popular leftist political
channels on youtube tend to center cishet white men. While a lot of this is
likely due to consious or unconsious biases in the way people consume content
and the way creators network with each other, it has also been suggested that
the youtube algorithm itself tends to reinforce this through it's recommendations.
I don't know exactly how I could go about studying this phenomena since obviously
the youtube api isn't going to let me pull any information about what videos are
being recommended to users, but I wonder if I might be able to find indirect
evidence of this by scraping the comments section. If a lot of people who comment
on youtuber A's videos also comment on youtuber B's videos, there is a good chance
that youtube is recommending youtuber A's content to youtuber B's audience and vice
versa.

### Toxic fanbases
One pattern that tends to repeat over and over online is people with a large 
social media following using their followers to attack others online. It
would be interesting to use something like the pagerank algorithm to see
which influencers are the most toxic based on how toxic the people that follow
them are and how toxic the followers of their followers are etc.

