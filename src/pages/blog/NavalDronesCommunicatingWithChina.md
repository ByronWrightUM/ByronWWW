---
layout: '../../layouts/BlogPost.astro'
title: 'UK Naval Drones Communicating with China'
date: '2026-08-11'
description: 'Can we trust electronics manufactured in China? Maybe not, but we can mitigate the risk.'
tags: ['Cybersecurity']
## tags currently in use (to be updated over time)
## 'General','AI','Teaching','Learning','Cybersecurity','DB and Data'
## 'IDM 1020','MIS 3520,'MIS 3500'
---

Over the last number of years, there's been a lot of hype about whether we can trust Chinese electronics. Here in Canada there was quite a kerfluffle about Huawei telecommunications equipment back in about 2020. More recently there are concerns about Chinese electric vehicles being spy machines that will report back sensitive information.

In Aug 2026, it was reported that Chinese manufactured cameras used on UK naval drones were communicating back to China. The headlines made it seem that whatever the camera saw was transmitted back to some sort of control centre. However, the reality was quite a bit more boring. Operational cameras sent data to indicate they were online, basically a functional test. Possibly more sloppy coding than nefarious.

See a summary here: [https://defence-blog.com/royal-navy-naval-drone-cameras-secretly-sent-data-to-china/](https://defence-blog.com/royal-navy-naval-drone-cameras-secretly-sent-data-to-china/)

What I found interesting is that something used for military communications was allowed to communicate with a random IP address on the internet. Not exactly a high security setup.

Once upon a time, a typical network configuration for business blocked incoming communication, but allowed anything outbound. Over time, the default in more networks is to limit the outbound communcation to increase security. Since this is a known issue in basic business configurations, it seems odd that it was overlooked for military communications.

So, is it bad that it's hard to verify the security of Chinese manufactured electronics? Yes.

However, in this case, it seems that some basic networking controls effectively allow you to monitor and mitigate the risk. Which is exactly what they did.
