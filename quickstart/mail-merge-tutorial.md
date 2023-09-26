---
description: Follow these simple steps to send your first emails with Mail Merge.
---

# Mail Merge Tutorial

First, make sure you have installed Mail Merge for Gmail from the [Google Workspace Marketplace](https://workspace.google.com/marketplace/app/mail\_merge\_for\_gmail\_how/57033717989). Once installed, let's see how to personalize and send your first emails.

{% embed url="https://youtu.be/eDfDZtL_daU" %}
A short video to cover the basics of Mail Merge for Gmail
{% endembed %}

## Personalize your email content

With Mail Merge for Gmail📣, **you can change the content of each email received** by each recipient. This is what we call personalization.

### Start with the Google Sheet content

The idea is simple, in your Google Sheet, **each row will represent an email.** The minimal requirement to send a campaign is to have a column with all the recipients _(Column "A" in the screenshot below)_.

<figure><img src="../.gitbook/assets/start with data" alt="Start with data. Pay attention to headers names"><figcaption><p>Start with data. Pay attention to header names</p></figcaption></figure>

You can add as many columns as you want, and you will be able to retrieve them in the template editor. _( Column Name / Company ...)_

### Customize your email template

In the template editor, You are now able to retrieve your Spreadsheet data to customize your emails, through what we call **merge tags.**

<figure><img src="../.gitbook/assets/highlight mergetag (1).png" alt="Headers become merge tags"><figcaption><p>Headers become merge tags</p></figcaption></figure>

Merge tags are simply names of your columns, surrounded with characters \{{ \}}. For instance, if you want to use the "Name" column in your template, bring it with \{{ Name\}}.

You don't have to type merge tags, just use our dropdown menu :

<figure><img src="../.gitbook/assets/use mergetag.png" alt="Merge tags becomes your data"><figcaption><p>Merge tags becomes your data</p></figcaption></figure>

## Personalize your email subject

To customize your email subject, you can also use Merge tags. For instance, if your Google Sheets contains a column "Name", **you can customize your email subject using merge tag** "\{{Name\}}" as shown below:

<figure><img src="../.gitbook/assets/spaces_tBoQpQrzJViUHu4Cv5ai_uploads_hvASE2iGp4kbzRqvnfgA_subject (1).webp" alt="You can customize the subject with merge tags too"><figcaption><p>You can customize the subject with merge tags too</p></figcaption></figure>
