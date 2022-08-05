---
nav_order: 1
title: Introduction
---

{% capture outcomes %}

| By the end of the workshop, you should be able to: |
| -----|
|**Understand** that different digital tools appropriate to various stages of higher degree research; |
| **Identify** and select at least one new digital tool appropriate to your own research workflow; |
| **Explain** how research data can be protected using security and backup tools; |
| **Demonstrate** simple data visualisation techniques using sample data; |
| **Locate** ongoing technical and research support from the University. |
{:.table}

{% endcapture %}

{% capture header %}{% include icon.html icon='mortarboard-fill' %} Learning outcomes{% endcapture %}
{% include card.html header=header text=outcomes %}

----

## Structure of the workshop

This workshop has five sections, reflecting the phases of research outlined by [Kramer](https://twitter.com/MsPhelps) {% include icon.html icon="twitter" %} and [Bosnan](https://twitter.com/jeroenbosman) {% include icon.html icon="twitter" %} of Utrecht University in their [extensive 2016 study](https://101innovations.wordpress.com) on scholarly tools (Kramer and Bosnan actually use seven phases, but we have simplified it to five).

{% capture ofcourse %}

Of course, a real research project does not neatly move from one phase to the next! You will be moving between them all the time. They are convenient categories in which we can place the kinds of tools that assist you when you are doing that kind of work.

{% endcapture %}
{% include alert.html text=ofcourse color="info" %}

This workshop is more of a show-and-tell than an interactive workshop. This is because we know not all tools will be relevant to all participants. Therefore, we present you with a selection of tools that we think may be useful. You are welcome to try, adopt and ask questions about any of them.

### Structure of the site

Each page on this site contains one or more topics, separated on the page by a horizontal line. The topics are listed at the top of each page, plus in the table of contents shown on the front page. Each topic presents some explanatory text, followed by a list of tools relevant to that topic. Then list will usually conclude with a recommendation. Finally, if it's relevant, there will be a list of related workshops offered by Griffith University. It looks like this:

{% capture exampletoolslist %}

- **[Some great tool](https:www.griffith.edu.au)**: Brief description of the tool.

- **[Another really great tool](https:www.griffith.edu.au)**: Another brief description.

{% capture examplerecommendation %}

**Our recommendation:** Really great tool #2. We think this is going to be the most useful for most researchers. Of course, you should make a judgement based on your own circumstances!

{% endcapture %}
{% include alert.html text=examplerecommendation color="primary" %}

{% capture relatedworkshops %}

- [Some great workshop](https://app.secure.griffith.edu.au/events/)

{% endcapture %}

{% include accordion.html title1="Related workshops" text1=relatedworkshops open=true %}

{% endcapture %}

<!-- This creates the heading text for the card, along with the icon -->
{% capture exampleheader %}{% include icon.html icon='balloon-heart-fill' %} An example list of tools{% endcapture %}

{% include card.html header=exampleheader text=exampletoolslist %}

### How we recommend things

We base our recommendations on a balance of factors, including:

- **Cost:** Is it free, or can be obtained for free?
- **Availability:** Is it available on all computing platforms, and easy to download and run?
- **Support:** Is support available through the University, or some other way?
- **Ease of use:** It is simple to get started if you're not familiar with it?
- **Data hygiene:** Are we reasonably confident that your data won’t be misused?
- **Open source:** All other things being equal, we will favour the open source option.

### Activities

Some pages include optional activities that you can undertake. They are indicated by a button on the page, like this: 

{% include button.html text="Go to this activity" link="#" color="primary" size=lg %}

----

## Workshop preparation

{% capture preparationblock %}

 There are a few pieces of software to install before you start this workshop, so you can take part in the activities. Click on each heading below to read instructions on installation.

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

{% capture activitytext %}
To start with, why not start by putting a number on your own digital toolbox? Take a moment to estimate how many digital tools you use in your research workflow. Once you have come up with a number, click the button below to see where you stand in relation to other researchers. 

{% capture averagetools %}
The average number of digital tools in a researcher's toolbox is 22. If you count your word processor, image program, notes program, email app and so on, you can see that this is actually a realistic number!

{% include figure.html img="tool-freq-dist.png" alt="Alt text" caption="Histogram of number of tools used by researcher" width="100%" %}

{% endcapture %}

{% include modal.html button="Show me" color="info" title="Show me the average number of tools used by other researchers" text=averagetools %}

{% endcapture %}

{% include jumbotron.html heading="Preliminary activity" text=activitytext %}


<!-- 
Learn-Static Lesson Template is a Jekyll project to create a simple lesson or workshop website, with a [Bootstrap](https://getbootstrap.com/)-based theme, designed for hosting on [GitHub Pages](https://pages.github.com/).

It features a sidebar navigation providing clear structure for step by step content.
The sidebar nav supports pages nested into sections to help organize your lesson content. 

All content is written using basic Markdown, making it simple to write, edit, and reuse lesson materials.

To use Lesson Template to create your own website  make a copy and replace the template content with your own!

### Why?

Rather than making slides for a workshop, why not make a website? 
It's easier to write, access, share, and reuse. 
GitHub and GitHub Pages makes this relatively straightforward.

Writing content in this simple, reuseable format makes for a better [Open Educational Resource](https://en.wikipedia.org/wiki/Open_educational_resources) since anyone can make a copy and adapt!

## GitHub Pages 

One amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/).
It provides free static web hosting from any repository.
Gh-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
Because it is free and a valuable transferable skill, this is a great option for teaching and learning.

Many organizations are using GitHub to collaboratively create and publish public workshop websites. 
For example: 

- [Programming Historian](http://programminghistorian.org/)
- [Software Carpentry](https://software-carpentry.org/), [Data Carpentry](http://www.datacarpentry.org/), [Library Carpentry](https://librarycarpentry.org/)
- this site!

{% capture text %}Note:
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.html text=text color=secondary %} -->
