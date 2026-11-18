---
layout: '../../layouts/BlogPost.astro'
title: 'Sometimes AI is Coding Magic'
date: '2026-11-18'
description: 'AI enhances power users'
tags: ['AI','MIS 3520']
## tags currently in use (to be updated over time)
## 'General','AI','Teaching','Learning','Cybersecurity','DB and Data','Interesting Content'
## 'IDM 1020','MIS 3520,'MIS 3500'
---

Sometimes I'm blown away at how good something can be when you use AI. In the early days of AI, I fought with it to get results I wanted. Now, more and more often, it gets things right on the first try.

I added a blog post to this site earlier today that included a table. When I reviewed it afterwards the formatting was just plain ugly.

![image](./images/BlogTableInitial.png)

I assumed that this could be fixed by changing the cascading style sheet (CSS) files that contain element formatting info, but definitely not my area of expertise. So, Copilot in Visual Studio Code to the rescue. I gave it the following prompt. Notice that I had enough proper terminology from web development to provide AI with useful instructions. It worked around my typo of "veyr".

![image](./images/BlogTablePrompt.png)

In 26 seconds, it worked through the issue and gave me a resolution.

![image](./images/BlogTableAISteps.png)

I was prompted to run Astro build but in my scenario it's not required. So, I said no.

The end result for the table formatting was the following.

![image](./images/BlogTableResults.png)

I could have asked for addtional tweaks like different colors but I'm happy with this simple results that makes the table much more readable. It even works well in light and dark modes.
