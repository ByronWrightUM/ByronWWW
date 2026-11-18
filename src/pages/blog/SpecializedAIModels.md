---
layout: '../../layouts/BlogPost.astro'
title: 'Specialized AI Models vs General AI Models'
date: '2026-11-18'
description: 'AI models tuned to specific tasks offer the promise of lower price and higher performance'
tags: ['AI']
## tags currently in use (to be updated over time)
## 'General','AI','Teaching','Learning','Cybersecurity','DB and Data','Interesting Content'
## 'IDM 1020','MIS 3520,'MIS 3500'
---

At the start of the AI boom, OpenAI (ChatGPT) and Anthropic (Claude) were touting the idea of artificial general intelligence (AGI). This is a very cool idea and captured the imagination of venture capital firms. Very much in the way that Tesla kept teasing self-driving cars while making little or very slow progress after a certain point, the AI companies kept creating more and more powerful general purpose AI models in the pursuit of AGI.

As the general AI models were fed more data, it seemed like magic and only a matter of time before AGI emerged. However, at some point a couple of years ago, talk of AGI faded and now we're on to agentic AI.

I'll declare my bias up front. I've been working in the Microsoft ecosystem for almost 30 years. I've seen predictions of Microsoft's demise multiple times and they always seem to come back. They're generally not a first mover, but they keep pushing at something until it works and they might have done something similar with AI.

Early on Microsoft hitched their AI fate to OpenAI. When Anthropic started to get better performance, it looked like Microsoft might be left behind. Eventually they added Claude as an option within Copilot, but there was nothing uniquely Microsoft. They were just a conduit to ChatGPT and Claude.

Microsoft AI is pursuing specialized models that are tuned to specific tasks and function at a lower cost than the frontier models from OpenAI and Anthropic. Here are the descriptions from [https://microsoft.ai/models](https://microsoft.ai/models):

| Model      | Description                                                                                                                      |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Thinking   | Built for the complex problems that matter most, with competitive reasoning and top SWE-Bench Pro results at a mid-weight price. |
| Cyber      | A cybersecurity model built into MDASH, our multi-agent vulnerability identification and remediation harness.                    |
| Code       | Helps your engineering team write better code faster, with a lightweight, agentic model built into GitHub Copilot and VS Code.   |
| Image      | Create stunning, design-ready images from any text or photo prompt, with best-in-class Arena ELO scores at a lower price.        |
| Transcribe | Turn noisy audio into precise, domain-specific transcripts, with leading FLEURS and Artificial Analysis accuracy scores.         |
| Voice      | Delivers expressive, low-latency speech that holds up across long generations.                                                   |
| Realtime   | A speech-to-speech model built for naturally flowing conversations in real-world enterprise applications.                        |
| Custom     | Your data, your rules. Fine-tune a model to fit your business with full privacy and control.                                     |

If your goal is to get things done, using specialized models makes sense to me. The pursuit of AGI is the home run that gets investors excited, but I'm not convinced it's cost effective (or even possible via large language models). When you have to tell Claude and ChatGPT "make no mistakes" to improve results, we're still a ways off.

If you'd like more details, see the Microsoft announcement from the Ignite conference: [https://microsoft.ai/news/microsoft-ignite-2026/](https://microsoft.ai/news/microsoft-ignite-2026/)
