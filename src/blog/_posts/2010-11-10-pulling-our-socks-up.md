---
title: Pulling Our Socks Up
authors:
- charles-mccathienevile
tags:
- features
- presto
- socks
- process
- testing
- coreblog
license: cc-by-3.0
---

<p>One of the things we are always doing at Opera is looking for bugs and fixing them. Anyone who <a href="http://bugs.opera.com/" rel="nofollow" target="_blank">files one</a> knows they get a number, whether it is a feature request or a rendering issue. But in the Core department we have begun work on a special bug. We also reached an important milestone... ... </p><!--more-->Our bugs internally are labelled by numbers, but also according to the product. So DSK-123 is a desktop bug, and so on. There is one bugs that somehow seems a bit special, a reminder of simpler times. We&#39;ve carried it across Bug Trackers as we have upgraded our systems. we&#39;ve watched it acquire duplicate reports. We&#39;ve often thought it would never amount to much, just a feature request among the many.<br/><br/>But we have finally decided the time has come. We have begun work on the bug CORE-1 (Missing support for SOCKS proxy). Naturally we read the feedback people sent (e.g. <a href="http://www.reddit.com/r/IAmA/comments/dtbcz/hey_reddit_join_the_opera_browser_team_for_an/" target="_blank">our recent Reddit AmA</a> where some core engineers where among the folks at Opera who volunteered to provide answers). We have noticed that recently instead of vanishing away as predicted (there are various workarounds that seem to suit most use cases) we are now getting more requests to do this. So in a future version of Opera you will actually get support for SOCKS proxies....<br/><br/>For those of you who follow the <a href="http://my.opera.com/desktopteam/blog/" target="_blank">desktop team blog</a> for the latest test releases, you may have noticed that they are now running presto 2.7 (the large number of core changes announced there is a clue). It&#39;s only a few weeks since we finished with 2.6 and made 2.7 the current version - and it&#39;s already in what Desktop are producing. So when it is actually ready it won&#39;t be a long delay to get it into a Desktop Opera build you can download.<br/><br/>This is what he had hoped to achieve with a change in our development process that has been going on for the last year or so. We have been working on the way we release upgrades of Presto to the teams who have to use it, to make it easier to take a latest release as the basis for a product. In this process, we have become much stricter on the criteria for integrating a task (whether a new feature, or work on something already there) into the mainline of Presto. For a year or so we&#39;ve been working on getting the process leaner and the results cleaner. A week or so ago, for the first time, we got our integration queue to zero - everything that was waiting to be integrated into the mainline was there.<br/><br/>This really means that we&#39;re successfully improving the quality of the core Presto code that we supply to the different platform teams, because integration requires stricter testing than ever before to meet the acceptance criteria - which means the integration guys making sure that what developer groups have done is improving Presto without introducing new problems.<br/><br/>Of course, it didn&#39;t last. Teams keep finishing their tasks, and submitting them for integration, which takes time. This is good - we want to have a short integration queue, meaning that real work has been done, but keep it short so everyone working on Presto can be using a latest and greatest build while being more confident than ever about its quality and stability, from Core developers to people finishing a product for a customer. Which means we can build something better than ever before... because that&#39;s what really gets us motivated :)