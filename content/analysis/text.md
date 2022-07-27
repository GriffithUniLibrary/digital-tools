---
section: Analysis
nav_order: 3
title: Text analysis 
topics: Sentiment analysis; Concept mapping
description: >
    The analysis of 'text as data' is becoming increasingly commonplace. It is a key aspect of the Digital Humanities field.
# youtubeid: moJgWrD6dwg
---

{% capture relatedworkshops %}

- [Leximancer workshops](https://app.secure.griffith.edu.au/events/search?sdata=leximancer)
- [Digital Texts and Tools for HASS Research](https://app.secure.griffith.edu.au/events/search?sdata=HASS)
- [Webscraping](https://app.secure.griffith.edu.au/events/search?sdata=scraping)

{% endcapture %}

{% include accordion.html title1="Related workshops" text1=relatedworkshops open=true %} 

{% capture textanalysis %}

- **[NVIVO](https://www.griffith.edu.au/student-computing/available-software)**: version 12 integrates with Endnote and other tools

- **[Leximancer](https://www.griffith.edu.au/student-computing/available-software)**: Leximancer isn't officially supported by the University (i.e. on-demand technical support isn't available) but training sessions are conducted several times per year. Check the [RED Workshops Calendar](https://app.secure.griffith.edu.au/events/category/researcher-education-and-development) or [contact RED](mailto:red@griffith.edu.au).

- **[MaxQDA](https://www.maxqda.com/)**: mixed methods analysis

- **[Voyant](http://voyant-tools.org)**: sentiment analyser

- **[JSTOR Text Analyser](https://www.jstor.org/analyze/)**

- **[JSTOR Labs](http://labs.jstor.org.libraryproxy.griffith.edu.au/)**: A variety of text analysis tools provided by JSTOR. Griffith maintains a subscription. 

- **[Gale Digital Scholar Lab](http://libraryproxy.griffith.edu.au/login?url=https://infotrac.gale.com/itweb/griffith?db=DSLAB)**: A collection of tools to build, clean and analyse text-based datasets. Griffith maintains a subscription.

{% endcapture %}

{% capture taheader %}{% include icon.html icon='chat-left-text' %} Text mining and sentiment analysis{% endcapture %}

{% include card.html header=taheader text=textanalysis %}

Want to try out analysing some text? This is fun!

{% include button.html text="Go to the Voyant activity" link="/content/activity-voyant.html" color="info" %}
