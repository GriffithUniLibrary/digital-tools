---
section_id: Discovery
nav_order: 4
title: Capture
topics: Document scanners; Voice to text
description: >
    Reduce the time-consuming task of converting analogue information like printed text and recorded voices into a digital format for analysis.
# youtubeid: moJgWrD6dwg
---

## Scanning and OCR

Document scanning and optical character recognition (OCR) has come a long way. You can get just as good quality results from a smartphone app as from most flatbed scanners.

{% capture scanners %}

The following apps all scan photos, documents and whiteboards, automatically straighten and crop the image and optionally read the text. They can all create multi-page PDFs. This is incredibly helpful if you are dealing with physical manuscripts or other written material.

- **Adobe Scan** ([Android](https://play.google.com/store/apps/details?id=com.adobe.scan.android&hl=en_US) and [iOS](https://apps.apple.com/us/app/id1199564834)): Scans documents and saves them as PDFs to Adobe Document Cloud. Requires a Creative Cloud subscription to save PDFs. 

- **Microsoft Lens** ([Android](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens&hl=en_AU&gl=US) and [iOS](https://apps.apple.com/au/app/microsoft-office-lens-pdf-scan/id975925059)): Microsoft's scanner tool. Also scans documents and saves as images or PDF. Can annotate scans with text. Requires Microsoft 365 subscription to save to OneDrive. 

- **SwiftScan** ([Android](https://play.google.com/store/apps/details?id=net.doo.snap&hl=en_AU&gl=US) and [iOS](https://apps.apple.com/us/app/swiftscan-document-scanner/id834854351)): Connects with several cloud services. Requires monthly subscription. 

- **Apple Notes**: The Notes app on iPhone scans multi-page documents as PDFs. An excellent free option if you have an iPhone.

{% capture bestscanner %}
**Our recommendation: Microsoft Lens**

Adobe Scan is more polished and has more features, but you are more likely to have a Microsoft 365 subscription, so go for the one that won't cost you money. If you happen to have a Creative Cloud subscription, then go for the Adobe option.

{% endcapture %}

{% include alert.html text=bestscanner color="primary" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-file-pdf'></i> PDF and document scanners" text=scanners %}

----

## Audio transcription

In the not so recent past, the only option to transcribe voice recordings into text was to painstakingly do it yourself, or to pay someone else to do it. Now, there are several tools that create fast and accurate transcriptions of your interviews or other recordings.

{% capture transcription %}

- **[eResearch speech-to-text service](https://www.griffith.edu.au/eresearch-services/speech-to-text)**: Griffith's eResearch team offers a speech to text service to Griffith researchers on a fee for service basis ($2 per audio hour). It uses Microsoft's Azure transcription service.

- **[YouTube](https://www.youtube.com)**: It turns out that YouTube is a convenient way to transcribe text, if you have no other option. You'll need to convert your audio into a video file, then upload it. YouTube will auto-caption the file.

- **[Adobe Premiere Pro](https://www.adobe.com)**: Premiere Pro also has an auto-captioning feature that you can use to generate and download transcriptions from.

- [Descript](https://www.descript.com): Originally a podcasting tool, Descript does a great job of transcribing and can distinguish between speakers on a recording. Two hours of transcription free per month.

{% capture besttranscription %}
**Our recommendation: eResearch**

Using Griffith's service means you benefit from the support, security and file storage offered by the University, plus someone else actually does the conversion work for you! And it's quite cheap.

{% endcapture %}

{% include alert.html text=besttranscription color="primary" %}

{% capture runneruptranscription %}
**Runner up: Premiere Pro**

If you want control over the whole process yourself, Premiere Pro is a good option. A license is free for staff. 

{% endcapture %}

{% include alert.html text=runneruptranscription color="info" %}

{% endcapture %}
{% include card.html header="Transcription tools" text=transcription %}

{% capture voicewarning %}

You will still need to review and correct your transcriptions. None of these tools are perfect. Sometimes they have difficulty with certain accents. Proper names, especially, can be missed or mistranslated.

{% endcapture %}
{% include alert.html text=voicewarning color="warning" %}
