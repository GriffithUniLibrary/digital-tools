---
section: Discovery
nav_order: 3
title: Literature search
topics: Citation trees; literature maps
description: >
    The increasing availability of open scholarly metadata, along with the ability of AI to make thematic connections between papers, has made a new generation of citation mapping tools possible.
# youtubeid: moJgWrD6dwg
---

## Automating your paper discovery

Don't just rely on the old methods of database searching! You can use automated tools to find and recommend similar or related papers to those you have. Some of them also help to visualise connections between the papers in your field or research project.

{% capture citmaps %}

- **[Google Scholar](https://scholar.google.com/scholar_alerts?view_op=list_alerts&hl=en)**: Create alerts in Google Scholar so you can be emailed when papers mathching specific keywords are published. A broad approach that might result in some irrelevant papers, but highly automated and convenient.

- **[Elicit](https://elicit.org)**: Enter your research question and Elicit will provide a list of relevant papers. Avoids the need to use exact keywords since it uses Language models like ChatGPT-3.

- **[Connected Papers](https://www.connectedpapers.com)**: A visual tool to help researchers and applied scientists find and explore papers relevant to their field of work. Papers are arranged according to their similarity. Even papers that do not directly cite each other can be strongly connected and very closely positioned. Connected Papers is not a citation tree.

- **[Open Knowledge Maps](https://openknowledgemaps.org)**: This free visualisation tool groups related topics together and presents papers on those topics in a packed-bubble type graph. Can filter for open access resources. 

- **[ResearchRabbit](https://www.researchrabbit.ai)**: Billing itself as 'Spotify for researchers', ResearchRabbit is the newest of the tools here. It generates recommendations based on your library and your preferences. It can also email you with new relevant research, like Google Scholar.

- **[Citation Gecko](https://www.citationgecko.com)**: Searches for and arranges related papers on a timeline

{% endcapture %}
{% include card.html header="Automated paper discovery and literature mapping" text=citmaps img="connected-papers-cropped.png" %}

{% capture scimaps %}

- **[VOSViewer](https://www.vosviewer.com)**: Describes itself as a 'software tool for constructing and visualizing bibliometric networks'. It can create visual networks of publications based on many factors, such as author, institution, co-citation or co-authorship.

- **[CitNet Explorer](https://www.citnetexplorer.nl/)**: CitNetExplorer is a software tool for visualizing and analyzing citation networks of scientific publications. It has not been updated in some time.

- **[CiteSpace](http://cluster.cis.drexel.edu/~cchen/citespace/)**: A free Java application for visualizing and analyzing trends and patterns in scientific literature. Maps can be drawn according to a variety of categories such as collaboration, co-citation, terms or institutions.

{% endcapture %}
{% include card.html header="Science mapping tools" text=scimaps %}

{% capture bestcitengine %}
**Our recommendation: All of them!**

No one of these tools does everything the others do. Why not set them all up so you have the best chance of locating the latest and most relevant papers in your field? Just make sure to define your Google Scholar alert keywords narrowly so you don't get swamped.
{% endcapture %}

{% include alert.html text=bestcitengine color="primary" %}