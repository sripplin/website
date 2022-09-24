---
layout: page
title: Post Archive
---

{% for post in site.posts %}
  * <span style="display: inline; font-size:0.9rem;" class="post-subtitle">[ **{{ post.title }}** ]({{ site.url }}{{ post.url }})</span> <span style="display: inline" class="post-date"><small>&raquo; <i class="fa-regular fa-folder-open" style="color: #969696; opacity: 0.80"></i> {% capture category_name %}{{ post.category }}{% endcapture %}<a style="white-space: nowrap; color: #969696" href="{{site.url}}/category/{{ category_name }}">{{ category_name }}</a>
   &raquo; {{ post.date | date: "%Y-%m-%d" }} &raquo; {% assign words = post.content | strip_html | number_of_words %}
    {{ words | divided_by:200 | at_most:25 }} mins </small></span>
{% endfor %}