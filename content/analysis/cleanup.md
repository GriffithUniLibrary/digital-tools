---
section_id: Analysis
nav_order: 4
title: Cleanup 
topics: OpenRefine
description: >
    Before you really go to work on your data, you should be sure that it is clean and usable.
# youtubeid: moJgWrD6dwg
---

{% capture relatedworkshops %}

- [Data Cleaning with OpenRefine](https://griffithunilibrary.github.io/data-cleaning-intro/)
- [Advanced Data Wrangling with OpenRefine](https://griffithunilibrary.github.io/advanced-data-wrangle/)

{% endcapture %}

{% include accordion.html title1="Related workshops" text1=relatedworkshops open=true %}

{% capture text %}
[OpenRefine](https://openrefine.org/) is a free, open-source tool for cleaning messy data. Do you have a survey data set with responses like 'no', nah', 'not really', and 'n/a' that all mean the same thing? Or rows of data that need to be split or combined? OpenRefine is very good at tidying this sort of thing.

Want to try it out? 

{% include button.html text="Go to the OpenRefine activity" link="/content/activity-openrefine.html" color="info" %}

{% endcapture %}

{% include card.html header="<i class='fas fa-broom'></i> Open Refine" text=text %} 