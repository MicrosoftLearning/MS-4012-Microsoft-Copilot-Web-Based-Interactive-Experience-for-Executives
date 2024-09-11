---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory

The demos for this course are based on the demos from the accelerator kit [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

It is important that you familiarize yourself with the demos prior to delivering this training. For several labs, you'll utilize sample documents and pre-created Teams meetings and emails.

- Pre-download all sample documents [here](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- Setup Teams meetings and email threads by following the instructions [here](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarize yourself with the Interactive experience found [here](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf).

    > **NOTE:** The Interactive Experience PDF file will download directly to device (downloads folder).

- Review the most current training deck [here](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx).

## Course Description

Explore the transformative potential of Microsoft Copilot and its impact on organizational efficiency. Designed for executives and business leaders without a Copilot license, this experience delves into the art of crafting effective prompts, offers an interactive experience, and demonstrates how Microsoft 365 Copilot can seamlessly integrate into daily business workflows to boost productivity and innovation.

The primary objectives for this delivery is to:

- Teach how to craft effective prompts
- Demonstrate Microsoft Copilot (web scope) and guide participants through an interactive experience
- Demonstrate Microsoft 365 Copilot - Microsoft Copilot (work scope), word, Outlook, and teams
- Invite participants to download and try Microsoft Copilot for Mobile

## Course Timing (Not finalized) 

| # | Topic                                 | Details                                                                                          | Total Time      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Craft effective prompts in Microsoft 365 Copilot | - Art of the prompt slide <br> - Prompt building slide <br> - Copilot lab slide | 5-10 minutes    |
| 2 | Microsoft Copilot on the web          | - Demo Microsoft Copilot (web mode) <br> - Interactive experience  <br> - Share your Experience slide | 35 minutes      |
| 3 | Microsoft 365 Copilot at work     | - Microsoft Graph slide <br> - Demo Copilot in Word, Microsoft Copilot (work mode), Copilot in Outlook, and Copilot in Teams <br> - Testimonial Slide <br> - Microsoft Copilot on Mobile slide | 25 minutes      |
|   |                                       |                                                                                                  | **Total time could push 70 minutes** |


Hyperlinks to each of the demos are listed below.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
