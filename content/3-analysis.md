---
title: Analysing your data
nav: Analysis
topics: Data cleaning, qualitative analysis, quantitative analysis, 
description: Analysing your data will happen over several stages.
---

{% include figure.html img="analysis.jpg" alt="Lego figure of Marie Curie with flasks" caption="What will I do with it all? (image by Reiterlied, licensed under CC BY-NC-SA 2.0)" width="75" float="left" %}

## Preparing to analyse

{% capture relatedworkshops %}

**Related workshops**

- [Data wrangling with OpenRefine](https://app.secure.griffith.edu.au/events/search?sdata=wrangling)

{% endcapture %}

{% include alert.html text=relatedworkshops color="warning" %}

{% include_relative 3-analysis-cleanup.md %}

___

{% include_relative 3-analysis-stats.md %}

___

{% include_relative 3-analysis-text.md %}

___

### Visualising your data

{% capture relatedworkshops %}

**Related workshops**

- [Data visualisation Basics](https://app.secure.griffith.edu.au/events/search?sdata=visualisation)
- [Excellent Graphics in R](https://app.secure.griffith.edu.au/events/search?sdata=graphics)
- [Data storytelling](https://app.secure.griffith.edu.au/events/search?sdata=storytelling)

{% endcapture %}

{% include alert.html text=relatedworkshops color="warning" %}


{% include_relative 3-analysis-visualisation.md %}

___

{% include alert.html text="**Fully analysed**, it's time to move to the [writing phase](5-writing.html). " color="success" %}
