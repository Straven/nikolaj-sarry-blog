---
title: 'Agile Metrics From Business Intelligence Tools'
date: 2024-11-22T00:06:49+02:00
Description: 'I have divided the content in this section according to the so-called "piracy metrics" or AARRR, i.e. Acquisition, Activation, Revenue, Retention and Referral.'
draft: false
Tags: ['agile', 'metrics', 'business-intelligence', 'business-analysis']
Categories: ['project-management']
DisableComments: false
thumbnail: 'images/agile-metrics-bit.png'
series:
  - agile-metrics
toc: true
---

Some people may be surprised by the metrics listed here. You might think that these are abstract metrics related to the business, while the development team should focus on traditional development metrics such as speed and defect rate. I think this is wrong! In fact - these are the most important metrics. These are your 'results', not your 'conclusions'. The whole team needs to know and think about these metrics. The greatest success you can achieve is when the whole team feels ownership and pride in what they are creating. Developers need to feel connected to the customers, their values and the results for the business they are helping.

I have divided the content in this section according to the so-called 'piracy metrics' or AARRR, i.e. Acquisition, Activation, Revenue, Retention and Referral.

![agile-metrics-business-intelligence-tools](/images/agile-metrics-bit.png)

## Acquisition

### Unique visitors

![unique-visitors](/images/2024/11/unique-visitors.png)

A common metric used to track visits to your website. The uniqueness of a visit is often determined by IP address deduplication. This metric is at the top of the 'pirate funnel' (each subsequent metric is a lower value than this one, usually expressed as a percentage or proportion) and this metric can be quite high. But you have to make sure you don't spend too much time on unique visitors. Some people in the startup community call this metric a 'vanity metric': because it's a big number and it's used to impress potential investors and the media. But if your site isn't blocked from pay-per-view, and there aren't many such sites, this metric doesn't mean much. If it's low, you should probably put marketing or PR efforts into increasing it, but if it starts to rise, you should focus your efforts on other funnel metrics.

## Activation

### Conversion rate

![conversion-rate](/images/2024/11/activation-cr.png)

You'll often hear the term used in different contexts. It can be used to refer to the types of conversions at different stages of your funnel: conversion of a website visitor to a subscriber or potential customer (buyer), conversion of a potential customer to a trial customer, conversion of a trial customer to a paying customer, and so on. The concept remains the same at each stage: what proportion of customers move on to the next stage of the funnel. Let's say we have 10,000 unique website visitors per month, 2,000 of whom subscribe to your newsletter or buy a subscription to your service/product. In this case, your conversion rate is 20%.

## Retention

### Monthly active users (MAU)

![mau](/images/2024/11/mau.png)

Monthly active users is a common metric, especially for social networks or SaaS (Software as a Service) providers. It is a measure of how many users interact with your website or product in a month. Some consider MAU to be the 'lifeblood' of an application or SaaS solution. I include this metric under Retention because it shows the number of people who support and are loyal to your product. Note that MAUs can refer to paid or free users, depending on the pricing model. Some have a free trial, some have a free plan, some have a paid plan only, etc.

## Revenue

There are different pricing models and therefore income generation models, so it is extremely difficult to choose which indicators to include. I have tried to include what I think are the most popular indicators that you are likely to have seen in the market and want to use.

### Conversion rate

![revenue-conversion-rate](/images/2024/11/revenue-cr.png)

Above we looked at this metric as an activation metric. Then we talked about the percentage of people at different stages of engagement in our funnel that are activated into customers. Here, the conversion rate refers to the percentage of people who have already been activated who become paying customers. The conversion method will of course depend on your pricing model (one-off, monthly, annual, API call cost). It is expressed as a percentage: successfully activated customers divided by the total number of customers and multiplied by 100.

### Regular monthly income (RMI)

![RMI](/images/2024/11/rmi.png)

This is a classic SaaS business metric. It's the number of your monthly active users multiplied by the cost per user. If you have different price tiers, you'll need to break them down into separate MAU categories and multiply by the cost within the category. Or you can use weighted revenue per user. Let's say 30% of your users pay $20 per month and 70% pay $50. In this case the weighted revenue would be 0.3*20 + 0.7*50 = 41. Multiply this by the number of users and you get your MRR.

### Throughput

![throughput](/images/2024/11/throughput.png)

This metric is based on a concept from Eli Goldratt's accounting theory, which is closely related to his theory of constraints. If you want to understand the details, I recommend reading his novel The Goal. Simply put, without going into the details of accounting, you can say that throughput is net sales revenue. That is, you take the revenue per unit sold, subtract the cost of the unit, and multiply by the number of units sold. This metric is more useful in manufacturing or retailing, where there is a clear cost per unit of goods (the cost of raw materials in manufacturing or the cost of goods sold in retailing).

The important point is not to amortise other operating income on a unit cost basis (as most cost accounting methods, such as activity-based costing, often advise). Software has no concept of cost per unit sold (software costs virtually nothing to mass produce or distribute, especially once the need for physical media for delivery disappears). So, net revenue: it's simply total revenue over a given period. This may seem too simple or useless, but there has been a major shift in thinking about throughput that is hard to explain without touching on traditional accounting methods.

### Cost of delay

![cost-of-delay](/images/2024/11/cost-of-delay.png)

This metric is considered the most important of all, especially in the context of product development. It is the cost of not releasing your product for a period of time. For example, if you can release your software today and make $1000 next month, then by not releasing it now, but in a month's time, you lose that $1000 in revenue. So your cost of delaying for a month is $1000. How you value the loss of revenue depends very much on your product and your circumstances, so it's impossible to give advice or guidance here. According to the book 'Principles of the Product Development Process' by Donald Reinertsen, many decisions about development priorities or resources can and should be converted to a cost per delay to get a simple answer. Remember that this is a metric for a specific period of time: a day, a week, a month, etc. For this reason, some calculate this figure as the cost of delay divided by the length of the period. This figure is sometimes used as a source of data for prioritisation.

## Referrality

### Loyalty Index (Net Promoter Score (NPS))

![NPS](/images/2024/11/nps.png)

This business metric is very important. It shows how likely your customers are to recommend you to others. The values of this indicator range from '-100' (no customer will refer another customer to you) to '+100' (every customer will refer another customer to you). The calculation is a little complicated. First, you have to do your research and ask your customers: "On a scale of 0 to 10, how likely are you to recommend us to a friend or acquaintance? Then you divide the responses into three categories: promoters (scores of 9 and 10), passives (7 or 8), detractors (6 or below). Then calculate the percentage of responses from promoters and detractors. Finally, subtract the percentage of detractors from the percentage of promoters. For example, if 50% of respondents were promoters and 30% were detractors, the NPS would be -20. The Loyalty Index is considered a very important metric for business growth. It is difficult to prove a strict cause and effect relationship because NPS is based on survey responses, which may not reflect actual behaviour. However, research shows that NPS is a very strong indicator of business success. Ignore it at your peril.

### Referral success rate

![Referral success rate](/images/2024/11/referral.png)

Your product or service may have a referral scheme where you offer customers a bonus or discount in exchange for promoting you or your product to others. This can be done in a variety of ways: a discount for successfully referring a friend, posting an ad on Facebook. Referral rate - the percentage of referrals that make a purchase. You can separately track the percentage of customers who agreed to participate in the referral programme (although this is a rather vain indicator because if none of the potential referrals take up the offer and do not become customers, it does not matter how many people participate in this programme).

## Conclusion

I hope you enjoyed this long post on agile metrics. I think I have covered all the important metrics that I think you will ever need. Remember that they should be used wisely, and that not everything that can be counted should be counted, and not everything that can be counted should be counted, and not everything that can be counted should be counted.
