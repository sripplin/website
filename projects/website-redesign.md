---
layout: post
title: "Website Redesign"
subtitle: 
category: projects
image_featured: 
image_root: website-redesign/
custom_excerpt: 
---

<!--more-->

<div style="font-size: 0.8em; margin-bottom:1em;">
    <i>Last Updated: 2022-11-15</i>
</div>

<center>
  <img class="img100" src="{{ site.imageurl }}{{ page.image_root }}design_screens_4.png"/>
</center>

I decided to redesign my website from scratch using Jekyll and Github pages. The primary motivation is that I discovered Jekyll (a blog-aware static site generator built on Ruby) so wanted to try it. I had zero prior experience with Ruby, Jekyll, or Liquid and very little with modern HTML/CSS. This seemed like the perfect new challenge.

This project also made a lot of sense to do to improve my website and how I interact with it. The key benefits are being able to use VS Code, own the source code on my local computer synced to Github, and use markdown to write and format posts. It is also free and open source so I’m not beholden to any one platform.

## Contents: <!-- omit in toc -->

- [What I was using before](#what-i-was-using-before)
- [The Project](#the-project)
- [Results](#results)
  - [Look](#look)
  - [Cost](#cost)
  - [Speed](#speed)
  - [Performance](#performance)
  - [UI](#ui)

## What I was using before

The last version of my website was built using Webflow. When launching my site a few years ago, I tried all of the basic builders such as Wix, SquareSpace, and Strikingly, but they were too simple and didn’t allow enough customization. So I went one level up with Webflow, which is more for serious website designers and mid-size enterprises.

Webflow has a learning curve, but I enjoyed learning about how modern webpages are made, although it is mostly with a no-code interface. This worked for a couple of years, but at the end of the day, it is a bit clunky for my use case - a 400-pound gorilla when something lighter and more customizable would do (without resorting to something like Wix).

## The Project

You can see the Github repo for my website with more granular details [here](https://github.com/sripplin/sripplin.github.io).

I started with a basic structure but did a lot of work on performance, style, and feature additions to get it to where I wanted:

- changed theme colors, font colors, link colors
- changed blog look and feel to a more modern design
- added dark mode. This was the most effort but worth it. Takes OS preference plus a toggle with persistence.
- optimized website for mobile, since the base theme is quite old the sizing didn't translate well to mobile.
    - optimized font sizes
    - made images responsive to sizing for web and mobile
- custom excerpts on home page
- added featured image to post previews on home page (though toggled off)
- added button via javascript to scroll back to top for posts

## Results

### Look
<center>
  <img class="img100" src="{{ site.imageurl }}{{ page.image_root }}look.png"/>
</center>

### Cost
<center>
  <img class="img100" src="{{ site.imageurl }}{{ page.image_root }}cost.png"/>
</center>

### Speed
<center>
  <img class="img100" src="{{ site.imageurl }}{{ page.image_root }}speed.png"/>
</center>

### Performance
<center>
  <img class="img100" src="{{ site.imageurl }}{{ page.image_root }}performance.png"/>
</center>

### UI
<center>
  <img class="img100" src="{{ site.imageurl }}{{ page.image_root }}interface.png"/>
</center>
