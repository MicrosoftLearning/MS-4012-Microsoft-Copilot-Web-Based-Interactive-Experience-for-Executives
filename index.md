---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory

The demos for this course are based on the demos from the accelerator kit ([Demo Guide and Talking Points.docx](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Allfiles/Demo_Setup/Demo_Guide_and_Talking_Points.docx)).

It is important that you familiarize yourself with the demos prior to delivering this training. For several labs, you'll utilize sample documents and pre-created Teams meetings and emails.

- Pre-download all sample documents here: [Demo Sample Docs](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Allfiles/Demo%20Sample%20Docs).
- Setup Teams meetings and email threads by following the instructions in this file: [Copilot Demo Guidance Prep Session](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Allfiles/Demo_Setup/Copilot_Demo_Guidance_%20Prep%20Session.docx).

Hyperlinks to each of the demos are listed below.


## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
