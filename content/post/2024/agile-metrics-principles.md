---
title: "Agile Metrics Principles"
date: 2024-11-11T10:38:56+02:00
Description: ""
Tags: ["agile", "project_management", "metrics"]
Categories: ["project-management"]
DisableComments: false
thumbnail: "images/wallpaper.jpg"
series:
  - agile-metrics
toc: true
---

In this series of articles I will give you information about agile metrics so that you have an understanding of what they are, how to measure them, and ways to use them.

The articles will cover all the possible metrics you are likely to want to use. You'll learn what they mean, when you can use them and how, and when you shouldn't use them.

I have divided all the metrics into five categories:
- Agile Project Tools metrics  - tracks the elements your team is working with.
- Lean Kanban metrics  - derived from Agile Project Tools or other sources.
- Metrics from Version Control Tools ( VCS) - tracks the commits that developers make to the codebase.
- Metrics from CI/CD Tools - taken from automated continuous integration and continuous delivery tools.
- Metrics  from Business Analytics - show how customers are using your software, how your business is growing, what customers think of your products, etc.

For each metric, we'll look at what it is, how to collect it, when to use it, and what you should be aware of.

## Principles of Agile Metrics

Before delving into agile metrics, it's important to understand some fundamental principles of what they mean and how to use them. I'm going to offer some insights that may surprise you or will be different from what is normally expected.

However, understanding the principles is an important first step, and you will get much more value from metrics if you have a proper understanding of their overall context and purpose.

## Principle #1: Agile metrics should be used by the team

Despite the obviousness of this principle, it is often neglected. In 99% of cases where agile metrics are used, this principle is not followed. In most cases because, someone outside the team, usually a manager, wants to “snoop”, “measure” or “evaluate” the team to “check productivity”. This is a bad approach for the following reasons:
- these metrics do not measure productivity;
- there is no easy way to measure productivity;
- productivity is not the primary measure of success - instead, you should look at the delivery of valuable software (I'd rather choose a non-productive team that delivers valuable software over a productive team that delivers useless software any day of the week);
- most metrics are starting points for discussions in team meetings, and if “managers” are looking at these metrics in a report, they are more likely to not take part in these meetings;
- the values of many metrics depend on the context around them, and the only people who understand these values are team members.

So the team should collect metrics, and the team should use and share them. Try to keep these metrics from leaving the team and going to outsiders as much as possible. The last thing you need is for some random middle manager to have a conversation with you about why Team A has a job completion rate of 40 and Team B has a job completion rate of 50. This is a completely unproductive conversation.

## Principle #2: Agile metrics should be surrounded by discussions

Numbers are important and can help tell a story, but they should be part of a live conversation, not an email or spreadsheet. Simply adding numbers to a presentation won't tell any information. If you want to tell a story, include numbers in the conversation about how you collected them, when, where, why, and why; what you plan to do with them once you have them.

## Principle #3: Agile metrics should be part of a specific study or experiment

As you'll see next, there are many metrics you can collect when developing software. If you just collect them all in hopes of figuring them all out at once, you will be dumbfounded and unable to do anything. Each metric tells its own story and can be used as part of a specific study (what are we having trouble with?) or experiment (how can we improve this part of the process?).

Ideally, the study or experiment will be the result of a retrospective or similar activity. For example, a team notices that they are having a problem meeting sprint goals. They decide to study time consumption during one sprint and notice that it has increased. They then run an experiment where they reduce the number of code checks and measure the time consumption again to see if it has changed. This is a good example of using metrics in a conversation, study, and experiment.
