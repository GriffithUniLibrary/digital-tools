---
section: Publication
nav_order: 2
title: Networking 
topics: Example Topic; Another Example
description: >
    Managing your profile and professional relationships is as important as your actual research. Use these social and networking tools to raise your academic profile.
# youtubeid: moJgWrD6dwg
---

{% capture profiletools %}

- **[Griffith Experts](https://experts.griffith.edu.au)**: All Griffith teaching staff have a profile on Griffith Experts.

- **[ORCID](https://orcid.org)**: Your ORCiD ensures all of your published research is associated with you, regardless of institution or project.

- **[Mendeley](https://www.mendeley.com)**: The reference manager also has sharing and social features.

- **[LinkedIn](https://au.linkedin.com)**: Promoted as a networking tool for professionals.

- **[Twitter](https://twitter.com)**: using hashtags to livetweet conferences is a favourite of researchers.

- **[Mastodon](https://joinmastodon.org)**: A federated (meaning many independent but interconnected instances) microblogging (i.e. 'twitter-esque') service. There are many Mastodon servers that might be of interest to you, for example [Scholar Social](https://scholar.social/about/more) is aimed specifically at academics and researchers.

{% capture relatedworkshops %}

- [Publish or perish? Multidisciplinary perspectives on what, when, with whom and why](https://app.secure.griffith.edu.au/events/search?sdata=perish)

{% endcapture %}

{% include accordion.html title1="Related workshops" text1=relatedworkshops open=true %} 

{% endcapture %}

<!-- This creates the heading text for the card, along with the icon -->
{% capture networkheader %}{% include icon.html icon='megaphone' %} Online profile tools{% endcapture %}

{% include card.html header=networkheader text=profiletools %}