---
layout: post
title: "Customer Based Corporate Valuation"
subtitle: 
category: projects
image_featured: 
image_root: cbcv/
custom_excerpt: 
---

<!--more-->

<div style="font-size: 0.8em; margin-bottom:1em;">
    <i>Last Updated: 2022-12-04</i>
</div>

In my last semester at Wharton, I took *MKTG776: Applied Probability Models in Marketing* with Prof. Peter Fader. The course is legendary: it is continually rated as the most difficult course at Wharton and also one of the best. I was enamored with the new tools and frameworks that hit the intersection of my interest in marketing, analytics, growth, finance, and consumer behavior. 

The course teaches probability models (right down to the derivation of the formulas) and their application in marketing (modeling consumer behavior such as adoption, churn, and spend), but also focuses on how to think critically about managerial problems and statistical methods.

I was especially intrigued by idea of *Customer Based Corporate Valuation (CBCV)*, developed by Prof. Fader and a former PhD student of his, Prof. Dan McCarthy, using the same concepts from the course. They co-authored the seminal paper, [*Customer-Based Corporate Valuation for Publicly Traded Non-Contractual Firms*](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3040422) (among many others), as well as co-founded [Theta Equity](https://www.thetaequity.com/), a CBCV consulting firm.

The idea was so compelling to me that I spent a couple of months after graduation learning the technical nuances of the methodology and applying it to Chewy, which had recently went public and disclosed just enough data to do a full analysis of the company.

### Result:

I was able to successfully model Chewy's customer dynamics, fitting models to analyze and predict customer behavior of acquisition, churn, and spend, that then built up into a full financial model and valuation of the company.

My writeup of the results is here: [Chewy's IPO: Customer Analytics and Valuation using Probability Models](https://steveripplinger.com/2019/08/12/chewys-ipo/)

For example, here are the survival curves for Chewy's customer cohorts and the model fit:

<center>
  <img class="img70" src="{{ site.imageurl }}{{ page.image_root }}chewy_curve.jpeg"/>
</center>

The full model is comprehensive, covering every aspect of the company's customers, financials, and valuation. Here is a glimpse of some of the visuals:

<center>
  <img class="img70" src="{{ site.imageurl }}{{ page.image_root }}chewy_dashboard.png"/>
</center>

### Impact

- I learned a lot and developed this skillset, which is a now core component of how I look at companies and think about growth/business models/etc.
- My model forecast proved to be very accurate, until the impact of COVID structurally changed Chewy's customer dynamics (for the better).