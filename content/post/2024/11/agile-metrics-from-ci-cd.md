---
title: 'Agile Metrics From CI/CD'
date: 2024-11-17T02:32:56+02:00
Description: 'These metrics come from continuous integration and continuous delivery tools. They are now part of a holistic DevOps tool chain and automated pipeline.'
draft: false
Tags: ['agile', 'agile-metrics', 'ci-cd']
Categories: ['project-management']
DisableComments: false
thumbnail: 'images/metrics-ci-cd.png'
series:
  - agile-metrics
toc: false
---

These metrics come from continuous integration and continuous delivery tools. They are now part of a holistic DevOps tool chain and automated pipeline.

## Test coverage

![Test coverage](/images/2024/11/test-coverage.png)

This is a very popular and ambiguous metric that many people get stuck on. It is the proportion of the code base that is covered by automated tests. More specifically, it is the proportion of methods for which one or more automated tests (unit or integration tests) are defined. While automated test coverage is a good idea, you should be careful with this metric. There are several reasons why this metric should be treated with caution:

- it does not discriminate between good and bad tests;
- it does not prevent developers from writing completely useless tests (just confirming the truth or something else with a test);
- it does not cover all end-to-end tests, because they do not test the method, but the entry points and UI components of the system.

High test coverage is not always a good thing. If you pay a lot of attention to it, and force developers to increase it, you may end up creating useless tests to improve it. This is bad, firstly because you get an unrealistic idea of real test coverage, and secondly because this practice starts to discourage developers.

This doesn't mean that you don't need to worry about test automation. It's important to remember that test coverage is a complex and subtle thing that can't be expressed in a number. That number can be part of a series of regular conversations, supported by multiple data points and regular code reviews.

A quick note: this metric can actually be obtained without using CI/CD tools, as it can be obtained from a version control system (some have it as a standard feature, others have plugins that can calculate it). I put it in this section because it is conceptually related to other CI/CD metrics.

## Good and bad builds

![Good and bad builds](/images/2024/11/good-bad-builds.png)

This is the percentage of builds that fail out of the total number of builds. This value should be small, ideally very small. Developers should run builds on their own machines (which should have a regularly updated codebase) before checking anything. If this number is higher than 5%, it is a bad sign.

## Escaped defects

![Escaped defects](/images/2024/11/escaped-defects.png)

This is the number of defects that were discovered after release. This metric is a bit like 'Number of Incidents Occurred' (which we'll talk about in the Service Management section below), but not quite. A bug may make it into a release, but never be considered an incident (it may not affect the customer experience, but it is still a bug). An incident can also occur when there is no defect. A defect is a problem in the code base. The number of escaped defects should be zero or close to zero.

## Unsuccessful deployments

![Unsuccessful deployments](/images/2024/11/unsuccessfull-deployements.png)

This is simply the number of failed deployments. You can count this number on a weekly, monthly or annual basis, depending on how often you deploy. Deployments can fail for a number of reasons, often due to configuration errors in the deployment tool. You can consider this value for the production environment only, or you can include other environments such as staging or test. This value should be zero or as close to zero as possible, especially for production environments. You should have no problem getting this number from your DevOps tool.

## Average time between releases

![Average time between releases](/images/2024/11/average-time-between-releases.png)

This metric is the average time between releases. This metric seems simple, but the following should be kept in mind:

- only the deployment in the production environment needs to be considered. Intermediate and test environments are not counted. This is because deployments in the test environment are quite frequent (several times a day);
- only successful deployments count;
- a release does not have to be for the customer; it can be a blue-green deployment, a pilot group, or enable/disable functionality, etc., but it is still a successful deployment. The decision to release to customers is a very different decision (and more often than not a business decision, not a technical one).

### How to use this metric

This metric is very simple: take the number of deployments over a period of time (e.g. three months) and divide it by the number of time intervals (e.g. the number of working days in three months). This will be your average time between deployments. You can use any period of time you like, but follow the guidelines below:

- the longer the time range, the better for sampling. Three months is a good starting point, but you can change it if it makes sense;
- use a moving time range: for example, do not take three months in total, but take the average of each month of the last three;
- don't arbitrarily change the time sample size to improve or worsen the statistics. Be honest and transparent.

## Changed Lines of Code ((CLOC)) per release

![Changed Lines of Code ((CLOC)) per release](/images/2024/11/changed-lines-of-code.png)

This indicator measures the average number of lines of code changed in a release. A changed line means whether it was a deletion, an addition or a modification. So to calculate this metric, you divide the total number of lines of code changed for the selected time period by the number of releases made during that time period. It may seem counterintuitive, but you should try to keep this number small and getting smaller. This is because small releases have fewer changes, less complexity and less risk. Many small releases are better than a small number of large releases.
