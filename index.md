---
title: Home
layout: default
---

# Digital Tools for Research

{% capture workshopinfo %}
Hi! This site is designed as a companion to [Griffith Library's](https://www.griffith.edu.au/library) Digital Tools for Research workshop, presented in collaboration with Griffith [RED](https://www.griffith.edu.au/research/research-services/researcher-education-development).
{% endcapture %}

{% include alert.html text=workshopinfo align="left" color="warning" %}

{% capture moreinfo %}
It can also be treated as a standalone, self-paced tutorial.
{% endcapture %}

{% include alert.html text=moreinfo align="left" color="info" %}

<!-- 
    {% include figure.html img="embarking.jpg" alt="Lego submarine floating on the water" caption="Preparing to embark (image by Reiterlied, licensed under CC BY-NC-SA 2.0)" width="75" float="left" %}
    -->

## About this workshop

Become familiar with a wide range of digital tools available to assist you throughout your research journey.

{% capture outcomes %}

By the end of the workshop, students should be able to: 

- Identify the various stages of higher degree research and understand that different digital tools are appropriate to each one, 
- Identify and select at least one new digital tool appropriate to their own research workflow,
- Explain the importance of protecting research data, as well as knowledge of what backup and storage options are available,
- Demonstrate simple data visualisation techniques using sample data, and
- Locate ongoing technical and research support from the University.

{% endcapture %}
{% include card.html header="Learning outcomes" text=outcomes %}

This workshop has five sections, reflecting the phases of research outlined by [Kramer](https://twitter.com/MsPhelps) <i class="fab fa-twitter" style="color:#00aced"></i> and [Bosnan](https://twitter.com/jeroenbosman) <i class="fab fa-twitter" style="color:#00aced"></i> of Utrecht University in their [extensive 2016 study](https://101innovations.wordpress.com) on scholarly tools (Kramer and Bosnan actually use seven phases, but we have simplified it to five).

{% include toc.html %}

Plus we include the following activities: 

{% capture activities %}
 - Data cleansing with OpenRefine
 - Data visualisation with Tableau {% endcapture %}
{% include card.html header="Workshop activities" text=activities %}

Of course, a real research project does not neatly move from one phase to the next! You will be moving between them all the time. They are convenient categories in which we can place the kinds of tools that assist you when you are doing that kind of work.

## Structure of the workshop

This workshop has more show-and-tell about it (in the online version, this might be more akin to browsing) than a typical workshop. The reason is that, with the variety of researchers that attend this workshop, we cannot be sure that all tools will be relevant to all participants (in fact, we can be sure that the opposite will be true!) Therefore, we will be presenting you with a selection of tools that we think may be useful, and you are welcome to try, adopt and ask questions about any of them. 

{% capture text %}There are a few things you need to do to get ready for this workshop. Specifically, you'll need to install some software in order to do the exercises listed above. Click on the button below to see instructions on preparing for this workshop.
{% endcapture %}
{% include card.html header="What do I need to do to get ready?" text=text %}

{% include button.html text="Workshop preparation" link="content/workshop-prep.html" color="primary" %}

## Preliminary activity

To start with, why not start by putting a number on your own digital toolbox? Take a moment to estimate how many digital tools you use in your research workflow. Once you have come up with a number, click the button below to see where you stand in relation to other researchers. 

{% capture text %}
The average number of digital tools in a researcher's toolbox is 22. If you count your word processor, image program, notes program, email app and so on, you can see that this is actually a realistic number!

{% include figure.html img="tool-freq-dist.png" alt="Alt text" caption="Histogram of number of tools used by researcher" width="100%" %}
{% endcapture %}
{% include modal.html button="Show me" color="info" title="Show me the average number of tools used by other researchers" text=text %}

{% include toc.html %}

------

{% include template/credits.html %}
