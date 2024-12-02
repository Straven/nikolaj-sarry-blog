---
title: 'Agile Metrics From Version Control System'
date: 2024-11-16T20:22:52+02:00
Description: 'Version control systems are a fundamental part of software development. Everyone uses them, even independent developers, because they too need to see the version history and be able to roll back. There are two common types of version control systems: centralised version control systems (CVSs such as SVN) and distributed version control systems (DVCSs), as they offer some important advantages. For the purposes of this guide, we will assume that you are using, or have access to, a DVCS. If you are using CVS, you will have a much smaller set of useful data, and you will also run into some inherent problems, so I recommend that you switch to a DVCS as soon as you have the chance.'
draft: false
Tags: ['agile', 'metrics', 'vcs', 'version-control', 'version-control-system']
Categories: ['project-management']
DisableComments: false
thumbnail: 'images/2024/11/agile-metrics-vcs.webp'
series:
  - agile-metrics
toc: true
---

Version control systems are a fundamental part of software development. Everyone uses them, even independent developers, because they too need to see the version history and be able to roll back. There are two common types of version control systems: centralised version control systems (CVSs such as SVN) and distributed version control systems (DVCSs), as they offer some important advantages. For the purposes of this guide, we will assume that you are using, or have access to, a DVCS. If you are using CVS, you will have a much smaller set of useful data, and you will also run into some inherent problems, so I recommend that you switch to a DVCS as soon as you have the chance.

## Number and percentage of pool requests that were accepted

![Number and percentage of pool requests that were accepted](/images/2024/11/number-pull-requests.webp)

One of the simplest metrics is simply the number of pool requests accepted, although it is much more useful to look at it as a proportion. Specifically, the percentage of accepted pool requests out of the total number of requests. If this number is high enough, it's probably a good thing, although you might want to make sure that some code reviews and discussions are still going on. If it's low, that's fine. Not all pool requests can be accepted. Sometimes developers come up with a different or better way of doing something close to the ideal, without even having to change the code (source code is a liability, not an asset). If the number is too low, this could be a warning sign of a problem between two or more developers. As always, make sure this metric is used as part of a series of conversations, not as a random report to be sent to management. This metric does a lot of damage when presented without considering the people and situations associated with it.

## Duration of open pool-requests

![Duration of open pool-requests](/images/2024/11/duration-pull-requests.webp)

This is the average amount of time the requester pool stays open. This is one of the interesting Goldilocks metrics, as you want it to be neither too high nor too low, but somewhere in the middle. If the pool is open for a long time, it may indicate that there are a lot of long discussions going on because of someone's work. And while discussions are good, you don't want them to go on forever: a decision has to be made. If every requester pool is open for a week, it's going to be very hard for the team to get a significant amount of work done. On the other hand, you don't want this rate to be low. If every pool request closes in five minutes, this is an indication that no one is reviewing or checking it. This could be because the team is not communicating effectively, or because someone is telling the team to 'hurry up and get on with it! Either way, a high or low score is a bad sign and you and the team need to find out why.

### How to use this metric

You should check it from time to time. Your DVCS should calculate it automatically, if not choose one that does.

## Number of comments per pool-requests

![Number of comments per pool-requests](/images/2024/11/comments-number.webp)

Number of comments per pool request. This metric is a bit like the previous one, in that instead of measuring the average amount of time a pool request has been open, we measure the average number of comments per pool request. Again, you want this to be neither too high (which would indicate that there is a problem in the team if someone gets 12 comments every time they post a pool challenge) nor too low (if everyone who posts a pool challenge gets one or zero comments, then no one is looking at it). Use this metric as well as the length of time the pool quest is open. Your DVCS should calculate and display this metric automatically.

## Code additions and deletions

![Code additions and deletions](/images/2024/11/code-add-delete.webp)

Your DVCS should have a graph showing code changes (additions and deletions) over time, usually measured in CLOC (number of lines of code changed). This is a good metric to look at regularly. You should look not only for frequency and quantity, but also for patterns. Are there a lot of spikes at weekends? People are working overtime, which is not good. Lots of additions and no deletions? Maybe no one is refactoring (since refactoring usually results in fewer lines of code in the system). Remember that source code is a liability, not an asset. The best system has a minimum number of lines of code, not millions.
