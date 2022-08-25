---
layout: post
title: "BackBlaze's Customer Analytics"
subtitle: 
category: customer_analytics
image_featured: c3_labels.png
image_root: backblaze_customer_analytics/
postdisclaimer: true
---

Customer cohort charts are becoming more popular. One of the latest is from [BackBlaze](https://www.backblaze.com/), a cloud storage company for individuals and enterprises that has 480k customers and generated $53.8M in revenue last year. The company recently filed its S-1 in advance of its upcoming IPO with some interesting customer disclosure.

<!--more-->

Here is the C3 chart:

<div class="images">
  <center>
  <img src="{{ site.imageurl }}{{ page.image_root }}c3_orig.png" style="width:80%"/>
  <p>Source: BackBlaze S-1</p>
  </center>
</div>

On the surface, it looks compelling - the cohorts are increasing modestly over time providing a growing base of revenue.

Before we can dive in, there is a key thing missing: pre-2016 cohort revenue. The company has been around since 2007 yet this chart only includes 2016 onwards, as evident by the just over $40M of 2020 revenue shown here versus the reported $53.8M.

## Contents <!-- omit in toc -->

- [Filling in the gaps](#filling-in-the-gaps)

## Filling in the gaps 

The first thing we can do is extract each data point:

<div class="images">
  <center>
  <img src="{{ site.imageurl }}{{ page.image_root }}c3_labels.png" style="width:80%"/>
  <p>Note: approximations based on pixel length</p>
  </center>
</div>

Next, we can add in pre-2016 data by taking the difference between the totals in this chart and revenue in the financial statements.

However, we run into a small snag: the company only includes the last two calendar years of financials in its IPO filings because it elects to be classified as an "[emerging growth company](https://www.sec.gov/smallbusiness/goingpublic/EGC)" which has lower disclosure requirements.

<div class="images">
  <center>
  <img src="{{ site.imageurl }}{{ page.image_root }}revenue_inception.png" style="width:80%"/>
  <p>This disclosure rule should be changed.</p>
  </center>
</div>