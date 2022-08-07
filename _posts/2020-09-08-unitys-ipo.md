---
layout: post
title: "Unity's IPO: What are the customer analytics of a game engine?"
subtitle: 
category: customer_analytics
image:
imageroot: unitys_ipo/ 
---

Unity Software Inc. recently filed its S-1 in advance of going public. Unity is the maker of a real-time 3D game engine that powers many 3D games and other content across numerous sectors. In this post, I focus on an under-discussed part of its IPO disclosure: its customer analytics.

<!--more-->

## Contents

- [Contents](#contents)
- [A customer-cohort-chart, sort of](#a-customer-cohort-chart-sort-of)
- [Filling in the gaps](#filling-in-the-gaps)
- [Insights:](#insights)
  - [1) A customer base with long lifetimes](#1-a-customer-base-with-long-lifetimes)
  - [2) Growing customer cohort revenue over time](#2-growing-customer-cohort-revenue-over-time)
  - [3) Healthy Net Revenue Retention on both cohort and corporate level](#3-healthy-net-revenue-retention-on-both-cohort-and-corporate-level)
  - [5) Large customers comprise most of Unity's revenue](#5-large-customers-comprise-most-of-unitys-revenue)
  - [5) Customer acquisition costs of $1.2 million in 2018 and $1.6 million in 2019](#5-customer-acquisition-costs-of-12-million-in-2018-and-16-million-in-2019)
  - [6) Customer payback period for $100,000 customers of 3-4 years](#6-customer-payback-period-for-100000-customers-of-3-4-years)
- [Conclusions](#conclusions)

## A customer-cohort-chart, sort of

In its S-1, Unity discloses a customer-cohort-chart (C3):

<center>
<img src="{{ site.imageurl }}{{ page.imageroot }}pkm.png" style="width:80%;"/>
</center>

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled.png)

These charts, as discussed in my Chewy IPO analysis, are amazing as they reveal so much about a company's customer acquisition, retention, and spend. 

At first glance, this chart looks pretty good: cohort revenue is increasing over time, which means that increasing customer spend is more than offsetting any churn. Each new cohort is entirely additive such that new customer acquisition is not required for growth.

...except there are two things missing on this chart. First, there is no y-axis. And second, there is no pre-2016 cohort revenue.

## Filling in the gaps

Let's fix that. Given that Unity discloses two data points for the 2018 cohort, we can populate the entire chart with very close approximations based on pixel length:

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%201.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%201.png)

Now, since we know the numbers for the above chart, we should be able to calculate the pre-2016 cohort revenue by subtracting 2016-2019 cohort revenue from the total annual revenue disclosed elsewhere. 

Unfortunately, we run into another problem with Unity's disclosure: despite being around since 2004, there is no pre-2018 annual revenue disclosed!

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%202.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%202.png)

The reason for the lack of disclosure is because Unity elected to be classified as an "Emerging Growth Company", which allows it to disclose a minimum of just two years of financial reporting versus the typical five years, along with [other significant benefits](https://www.sec.gov/smallbusiness/goingpublic/EGC).

From some other line items I was able to back out 2017 revenue of $290 million, but it is not possible to go back any further than that.

Putting all of this together, the x-axis shrinks to 2017 onwards, but we can still add pre-2016 cohort revenue to the C3 chart resulting in a more complete picture:

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%203.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%203.png)

This chart, along with other disclosures, allows for further analysis and insights.

## Insights:

### 1) A customer base with long lifetimes

Pre-2016 cohort revenue comprised exactly 50% of total revenue in 2019. This is reasonable given the company has been around for so long. Importantly, this means that Unity has many customers that have been with it for many years.

### 2) Growing customer cohort revenue over time

For recent cohorts, customer spend over time looks like this:

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%204.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%204.png)

Interestingly, there was a slight downward trend in cohort revenue from 2016-2018, though that has been reversed with strong first year revenue from the 2019 cohort.

### 3) Healthy Net Revenue Retention on both cohort and corporate level

Another way of looking at customer spend is net revenue retention (or "dollar-based net expansion rate"), which is above 100% for all of Unity's cohorts, including the pre-2016 cohort:

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%205.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%205.png)

Interestingly, each cohort seems to converge to the 120%-130% range and stabilize there.

This reconciles well with Unity's reported disclosure (again only for 2018 and later):

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%206.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%206.png)

This means that 2019 revenue would have grown 33% without any new customers. Unity's actual growth in 2019 was 42% because it did add new customers. Growth is much easier when it is already baked in from existing customers!

This process of a growing base of customers that spend more each year is why a company like Unity can put up stellar growth numbers, and generally speaking, is the key to the success of SaaS companies. I believe it is also the key to understanding why they typically trade at relatively high multiples.

For perspective, 133% net dollar retention is fantastic and puts Unity near the high end of SaaS companies:

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%207.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%207.png)

[Source](https://medium.com/iconiq-capital/full-disclosure-the-importance-of-business-fundamentals-1b77361c303)

### 5) Large customers comprise most of Unity's revenue

For the rest of the post, we will focus on Unity's >$100,000 customers, as Unity uses this as a cut-off for some of its disclosures, including these two charts:

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%208.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%208.png)

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%209.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%209.png)

Some simple math gets us to average revenue of $668k per customer, which is on an upward trend.

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%2010.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%2010.png)

### 5) Customer acquisition costs of $1.2 million in 2018 and $1.6 million in 2019

Focusing on these $100,000 customers, we can enable some analysis if we make the following assumptions:

- New $100,000 customers are actually new "customers acquired" (even if they may have been customers for a while at a smaller scale).
- $100,000 customer retention (past and future) is 99%. This is based on Unity's only disclosure about customer retention in its entire S-1: "As of June 30, 2020, we had 716 of these customers and a gross retention rate of 99%"
- All marketing spend in a period is attributed to new $100,000 customers. This is not the case in reality, but marketing expense as a capital investment is a useful way to think about CAC.

All of these are flawed, but it is the best we can do given the limitations.

Based on these assumptions and Unity's disclosure about its number of $100,000 customers, along with an extrapolation to get an estimate of the number of customers at the beginning of 2018, we can calculate that Unity added 116 new $100,000 customers in 2018 and 111 new $100,000 customers in 2019.

Unity's marketing expense was $134 million in 2018 and $174 million in 2019, resulting in CAC of $1.2 million in 2018 and $1.6 million 2019.

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%2011.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%2011.png)

### 6) Customer payback period for $100,000 customers of 3-4 years

Using the above calculations, we can calculate a payback period with a few additional assumptions:

- Contribution margin stays constant at the the 2019 level of 78.1%
- Cohort revenue continues to expand at 120%

For the 2018 and 2019 cohorts, we can calculate a payback period of 4 years and 3 years, respectively.

![Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%2012.png](Unity's%20IPO%20What%20are%20the%20customer%20analytics%20of%20a%20g%20a8777997f6eb4305863ce46192a218bb/Untitled%2012.png)

It is difficult to qualitatively assess how good this is without context around how long customers actually stick around, but on the surface given Unity's relatively sticky product, this seems to be reasonably healthy.

## Conclusions

Without more disclosure it is difficult to go beyond this analysis to calculate other metrics such as customer lifetime value, NPV of a customer, and so on. Further, it would be difficult to turn this into a full-fledged customer-based corporate valuation model. That said, on the surface, Unity's  customer analytics and economics appear to be positive.

This post has been an exercise in what can be done with limited information and was mostly to satisfy my own curiosity piqued by a C3 chart with no y-axis. The scope of this post is limited and is not a comprehensive analysis of the company. This is a high-profile IPO so there are a lot of well-done pieces on the company, which you should be able to find if interested.

It will certainly be interesting to see Unity's valuation at the IPO and how the company performs thereafter.