---
section: Preparation
nav_order: 2
title: Security 
topics: Password managers; Passkeys
description: >
    Just like backups, the best security protocol is the one you will use. 
# youtubeid: moJgWrD6dwg
---

## Passwords

Many (too many) people re-use the same password or minor variations across multiple sites. _This is a terrible idea._ If one of those sites is compromised, then all of them are.

{% capture pwned %}

**Have you been 'pwned'?** Data breaches, in which thousands or millions of user accounts and passwords are leaked on the internet, happen regularly. You might be shocked to find that one of yours is among them. Enter your email address at [HaveIBeenPwned.com](https://haveibeenpwned.com) to see how many data breaches it's been involved in.

{% endcapture %}
{% include alert.html text=pwned color="danger" %}

### Passwords vs passphrases

The best *password* to use is a *passphrase*. The *length* of your password is more important than whether it includes special charaters, numbers and so on.

{% capture passphrase %}

{% include figure.html img="password_strength.png" alt="Comic explaining why passphrases are superior to complex passwords" caption="This comic by XKCD (https://xkcd.com/936/) explains it best. Published under a CC-BY-NC 2.5 License." width="100" %}
{% endcapture %}
{% include alert.html text=passphrase color="info" %}

### Password managers

The best way to keep your passwords *different and secure* is to use a password manager. Getting used to using a password manager is a great investment in your overall experience of using the Internet. Most password managers have browser plugins that can fill login forms automatically. 

{% capture pwmanagers %}

 - **[LastPass](https://www.griffith.edu.au/passwords/lastpass)**: Griffith's supported password manager. It is available to all staff. 

 - **[Bitwarden](www.bitwarden.com)**: free and open source, multiplatform, simple to use. Very modern and well-regarded.

 - **[1Password](https://1password.com)**: high quality commercial (paid) option. It's been around along time and has a good reputation.

 - **[Dashlane](https://www.dashlane.com)**

{% capture pwrecommended %}
**Our recommendation: Bitwarden**

Although LastPass is a partner of Griffith and is offered free to staff, the app is not as seamless as Bitwarden, and your license will not come with you if you leave Griffith. For that reason, we recommend going with Bitwarden. 
{% endcapture %}
{% include alert.html text=pwrecommended color="primary" %}

{% endcapture %}
{% include card.html header="<i class='bi bi-key-fill'></i> Most popular Password managers" text=pwmanagers %}

{% capture browser %}
You could, but you would be missing out on a few of the key benefits of password managers, like checking that your passwords aren't being reused across services, generating new passwords for you and syncing your passwords across mobile and desktop devices.
{% endcapture %}
{% include modal.html button="Why can't I just let my browser remember my passwords?" color="info" title="Why not save in a browser" text=browser %}

----

### The future is passwordless

{% capture passkeys %}

Soon, there won't even be a need to keep a password manager handy, let alone remember all you passwords. A new standard being adopted and promoted by [all major technology vendors](https://fidoalliance.org), will allow your device (whether it's a computer or a mobile device) to generate unique, unguessable and unhackable login keys. Because they're stored by your device, you'll never forget them. And because you never see them, no scammer can ever trick you into divulging them.

Here's a [video from Apple's 2022 Developer Conference](https://developer.apple.com/videos/play/wwdc2022/10092/) that explains things in more depth.

{% capture loginalert %}
Expect passkeys to become a login option for many of the major technology platforms in the next 12-24 months.
{% endcapture %}
{% include alert.html text=loginalert color="warning" %}

{% endcapture %}
{% include card.html header="About passkeys" text=passkeys %}