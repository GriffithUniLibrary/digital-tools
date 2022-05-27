{% capture surveys %}

{% capture gurmawarning %}

**Get survey design advice first**

Creating an online research survey should come long after you've carefully designed and validated your survey. We suggest you attend one of the workshops above. You can also [Get advice from a qualified statistician](https://www.griffith.edu.au/research/research-services/researcher-education-development/statistical-advice).
{% endcapture %}

{% include alert.html text=gurmawarning color="danger" %}

The following two survey tools are provided and supported by Griffith. We recommend that you use one of these for your research. 

 - **[Lime Survey](https://prodsurvey.rcs.griffith.edu.au/doco2/)**: fast to develop, flexible and mobile-friendly. 

 - **[RedCap](https://www151.griffith.edu.au/redcap/)**: better suited to clinical and longitudinal studies.
 
 > [Workshops](https://www.griffith.edu.au/research/research-services/researcher-education-development/workshop-calendar) and [video resources](https://www.youtube.com/playlist?list=PLOtTT7TqB2izC3THIFCokfIh5DwlOPePH) are available.

{% capture whysurveys %}
REDCap and LimeSurvey are hosted on Griffith servers and managed by the eResearch team. This means:

- Your research data is securely backed up and archived according to Griffith's data retention policy,
- Australian data laws apply,
- [Workshops](https://www.griffith.edu.au/research/research-services/researcher-education-development/workshop-calendar) are available for both tools,
- [video resources](https://www.youtube.com/playlist?list=PLOtTT7TqB2izC3THIFCokfIh5DwlOPePH) are available, and;
- Technical support is avaiable for both tools.

{% endcapture %}

{% include modal.html button="Why are these tools recommended?" color="info" title="Why use LimeSurvey and REDCap" text=whysurveys %}

{% capture whichsurvey %}

This is a simple comparison of the key features of LimeSurvey and REDCap. If you're not sure which one you should use, the best thing to do is [discuss it with us](https://intranet.secure.griffith.edu.au/library/forms/help). 

{% include figure.html img="survey-comparison.png" alt="Comparison chart" caption="Feature comparison between LimeSurvey and REDCap" width="100%" %}

{% endcapture %}

{% include modal.html button="Help me to choose one" color="primary" title="Which survey tool should I use?" text=whichsurvey %}

**Alternative options**

These options are popular, but don't come with any support from the University. 
- [Google Forms](https://docs.google.com/forms/)
- [Microsoft Forms](http://forms.office.com)
- [Survey Monkey](https://www.surveymonkey.com)
- [Qualtrics](https://www.qualtrics.com) is popular in psychology. Griffith no longer holds a license so it will not be free for you to use.

{% endcapture %}

{% include card.html header="<i class='fas fa-poll'></i> Survey Tools" text=surveys title="Griffith supported survey tools" %}

{% comment %}
{% capture surveysalt %}
These options are popular, but don't come with any support from the University. 

 - [Google Forms](https://docs.google.com/forms/)
 - [Microsoft Forms](http://forms.office.com)
 - [Survey Monkey](https://www.surveymonkey.com)
 - [Qualtrics](https://www.qualtrics.com) is popular in psychology. Griffith no longer holds a license so it will not be free for you to use.
{% endcapture %}
{% include card.html header="Other options" text=surveysalt %}

{% endcomment %}
