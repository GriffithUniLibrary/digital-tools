---
title: Home
layout: default
description: Become familiar with a wide range of digital tools available to assist you throughout your research journey.
---

# Digital Tools for Research

{% capture workshopinfo %}

This site is designed as a companion to [Griffith Library's](https://www.griffith.edu.au/library) Digital Tools for Research workshop, presented in collaboration with Griffith [RED](https://www.griffith.edu.au/research/research-services/researcher-education-development). It can also be treated as a standalone, self-paced tutorial.

{% endcapture %}

{% include alert.html text=workshopinfo align="left" color="info" %}

<!-- 
    {% include figure.html img="embarking.jpg" alt="Lego submarine floating on the water" caption="Preparing to embark (image by Reiterlied, licensed under CC BY-NC-SA 2.0)" width="75" float="left" %}
    -->

{% include toc.html %}

## About this workshop

> Become familiar with a wide range of digital tools available to assist you throughout your research journey.

{% capture outcomes %}

By the end of the workshop, you should be able to: 

- Identify the different digital tools appropriate to various stages of higher degree research;
- Identify and select at least one new digital tool appropriate to your own research workflow;
- Explain how research data can be protected using security and backup tools;
- Demonstrate simple data visualisation techniques using sample data; and
- Locate ongoing technical and research support from the University.

{% endcapture %}
{% include card.html header="Learning outcomes" text=outcomes %}

This workshop has five sections, reflecting the phases of research outlined by [Kramer](https://twitter.com/MsPhelps) <i class="fab fa-twitter" style="color:#00aced"></i> and [Bosnan](https://twitter.com/jeroenbosman) <i class="fab fa-twitter" style="color:#00aced"></i> of Utrecht University in their [extensive 2016 study](https://101innovations.wordpress.com) on scholarly tools (Kramer and Bosnan actually use seven phases, but we have simplified it to five).

Of course, a real research project does not neatly move from one phase to the next! You will be moving between them all the time. They are convenient categories in which we can place the kinds of tools that assist you when you are doing that kind of work.

## Workshop structure

This workshop has more show-and-tell about it (in the online version, this might be more akin to browsing) than a typical workshop. The reason is that, with the variety of researchers that attend this workshop, we cannot be sure that all tools will be relevant to all participants (in fact, we can be sure that the opposite will be true!) Therefore, we will be presenting you with a selection of tools that we think may be useful, and you are welcome to try, adopt and ask questions about any of them.

{% capture activities %}

 - Data cleansing with OpenRefine
 - Data visualisation with Tableau {% endcapture %}
 
{% include card.html header="Workshop activities" text=activities %}

## Preparation

{% capture preparationblock %}There are a few things you need to do to get ready for this workshop. Specifically, you'll need to install some software in order to do the exercises listed above. Click on the button below to see instructions on preparing for this workshop.

<!-- {% include button.html text="Show me what I need to install" link="content/workshop-prep.html" color="primary" %} -->

{% include alert.html text="There are a few pieces of software to install before you start this workshop, so you can take part in the activities." color="primary" %}

{% capture installteams %}

Microsoft Teams is a collaboration tool that provides chat, videoconference and file sharing. This workshop will be conducted using Teams. It is possible to run Teams inside a web browser but you will find it much more convenient to download the desktop application.

1. Go to the [Teams download page](https://teams.microsoft.com/downloads)
2. Click `Download Teams`
3. Complete the installation per your operating system

{% endcapture %}

<!-- {% include card.html header="<i class='bi bi-mortarboard-fill'></i> Install Microsoft Teams" text=installteams %} -->

{% capture installtableau %}

Tableau is a data visualisation software. There are two versions: Tableau Public and Tableau Desktop. Tableau public is free, however your visualisations must be saved in the [Tableau Public Gallery](http://public.tableau.com/gallery/) and therefore is not suitable for confidential or sensitive data. Tableau desktop allows you to connect to more data sources and to save your visualisations locally to your computer. Students and Instructors are eligible for a free one-year license.

### Instructions for Tableau Public

1. Go to the [Tableau Public download page](https://public.tableau.com)
2. Enter your email address
3. Click on the download link in your email
4. Complete the installation per your operating system

### Instructions for Tableau Desktop

1. Go to the [Tableau Desktop download page](https://www.tableau.com/en-au/products/desktop/download)
2. Enter your email address
3. Click on the download link in your email
4. Complete the installation per your operating system
5. Compete the [student license application form](https://www.tableau.com/academic/students#form)
6. Wait for Tableau to confirm your status and send you your license by email
7. Enter your license details in the Tableau application

{% endcapture %}

<!-- {% include card.html header="<i class='fas fa-chart-pie'></i> Install Tableau" text=installtableau %} -->

{% capture installopenrefine %}
1.	Go to the [OpenRefine download page](https://openrefine.org/download)
2.	Click on the latest official distribution for your operating system
3.	Complete the installation per your operating system
{% endcapture %}

<!-- {% include card.html header="<i class='fas fa-table'></i> Install OpenRefine" text=installopenrefine %} -->

{% include accordion.html title1="Install Teams" text1=installteams title2="Install Tableau" text2=installtableau title3="Install OpenRefine" text3=installopenrefine %}

{% endcapture %}

{% include card.html header="Install required software" text=preparationblock %}

## Preliminary activity

To start with, why not start by putting a number on your own digital toolbox? Take a moment to estimate how many digital tools you use in your research workflow. Once you have come up with a number, click the button below to see where you stand in relation to other researchers. 

{% capture averagetools %}

The average number of digital tools in a researcher's toolbox is 22. If you count your word processor, image program, notes program, email app and so on, you can see that this is actually a realistic number!

{% include figure.html img="tool-freq-dist.png" alt="Alt text" caption="Histogram of number of tools used by researcher" width="100%" %}

{% endcapture %}

{% include modal.html button="Show me" color="info" title="Show me the average number of tools used by other researchers" text=averagetools %}

{% include toc.html %}

------

{% include template/credits.html %}
