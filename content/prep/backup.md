---
section_id: Preparation
nav_order: 2
title: Data management
topics: Storage; Reliability; Sync; Backup
description: >
    Find a place to put your research data. Don't lose it. Keep it secure.
# youtubeid: moJgWrD6dwg
---

Carefully considering your research data management early can save you a lot of headaches later. For example, your data storage location is critical. It needs to be three things: 

- Reliable
- Backed up
- Secure

## Reliability

It's advisable to synchronise a copy of your research data to a cloud service. Cloud providers host data on servers with 'failover redundancy', meaning if one server ever fails, another is ready to take its place instantly. This is how they can advertise '99.999% uptime'.

{% include modal.html button="What do you mean by 'reliability'?" color="secondary" title="About reliability" text="Reliability means there's a very low chance that the medium you've recorded your data on will fail. Modern computer hard drives are fairly reliable, but every drive will fail eventually. Laptop hard drives in particular can be less reliable." %}

{% capture syncoptions %}
- **[Cloudstor](https://cloudstor.aarnet.edu.au)**: powered by AARNet (The Australian Academic Research Network) and provides students and researchers with a Terabyte of free, ultra-fast storage. It's easy to set up and works just like Dropbox.

{% capture cloudstorwarning %}

Warning: AARNet has advised that it is [decommissioning its Cloudstor service](https://support.aarnet.edu.au/hc/en-us/articles/5697089309711) at the end of 2023. If you have data stored there you should investigate an alternative storage location.

{% endcapture %}
{% include alert.html text=cloudstorwarning color="warning" %}

- **[OneDrive](https://griffitheduau-my.sharepoint.com/)**: 1TB of space is provided to you by Griffith. Integrates with other Microsoft 365 services.

- **[Google Drive](https://www.google.com/drive/)**: Everyone knows this one.

- **[Dropbox](https://www.dropbox.com/)**: Everyone knows this one too.

{% capture cloudstor %}
**Our recommendation: Microsoft OneDrive**

Since Cloudstor is being decommissioned, our recommendation is to use OneDrive. You get a lot of space and it integrates with your Griffith account. Microsoft's Australian data is stored in data centers in Sydney so it is subject to Australian data protection laws. 
{% endcapture %}

{% include alert.html text=cloudstor color="primary" %}

<!-- Related workshops code snippet -->
{% capture relatedworkshops %}
- [Research data management](https://griffithunilibrary.github.io/research-data-management/)
{% endcapture %}
{% include accordion.html title1="Related workshops" text1=relatedworkshops open=true %}
<!-- End related workshops code snippet -->

{% endcapture %}

{% include card.html header="<i class='fas fa-sync'></i> Online storage & sync options" text=syncoptions img="storage-cropped.png" %}
___

## Backup

You should run a backup tool *in addition* to the services above. Your best, most secure option is to backup both to a physical hard drive and to an online service.

{% capture warning %}
**Remember:** sync is not the same as backup!
{% endcapture %}
{% include alert.html text=warning color="danger" %}

{% capture backupmodal %}
Because when you're syncing, if you delete something from your computer, it's also deleted from the remote copy. That's the **opposite** of a backup!
{% endcapture %}

{% include modal.html button="Really? Why not?" color="primary" title="Why is a sync not a backup?" text=backupmodal %}

{% capture backupoptions %}
 - **[Griffith Research Storage](https://research-storage.griffith.edu.au)**: built on the same technology as Cloudstor and is very fast. Research Vault is available for you to store data you are no longer actively using. Here is a [handy questionnaire](https://research-storage.griffith.edu.au/compare) to help you decide Griffith Research Storage can help you.

 - **[Arq Backup](www.arqbackup/com)**: use Arq to back your computer up to your Cloudstor or to your OneDrive. It's not free, but the $50 license is less than the cost of a hard drive and makes backing up completely automatic.

 - **[Backblaze](https://www.backblaze.com)**: popular, paid.

 - **[RSync](https://rsync.samba.org)**: RSync is a command-line tool for syncing local folders with an external hard drive or network drive.
{% endcapture %}
{% include card.html header="🛰 Online backup options" text=backupoptions %}

{% capture hdbackups %}
 - Time Machine (Mac)

 - Windows Backup (Windows 10)

 - Drag-and-drop (the worst option)

 {% capture timemachine %}
**Our recommendation: Your operating system**

The best backup is the one you will use. That means set-and-forget is best. Buy a simple external hard drive and leave it plugged in to your computer, or place a weekly calendar reminder to plug it in. Let the operating system do the rest. 
{% endcapture %}

{% include alert.html text=timemachine color="primary" %}

 {% endcapture %}

{% include card.html header="💽 Hard-drive backup options" text=hdbackups %}

{% capture why %}
Because (a) you will inevitably forget to do it at some point, and (b) each new copy replaces what was there before meaning you can't recover older versions of your work.
{% endcapture %}
{% include modal.html button="Why is drag-and-drop the worst way to back up?" color="primary" title="Why drag and drop is a bad idea" text=why %}
