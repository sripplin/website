---
layout: page
title: Post Archive
---

{% for post in site.posts %}
  * <span class="post-subtitle" style="display: inline; font-size:1rem; line-height: 110%; color:var(--link-color);">[ **{{ post.title }}** ]({{ site.url }}{{ post.url }})</span>
    <span class="post-subtitle" style="display: inline; color:var(--main-subtitle-color);">
      {%- if post.subtitle and post.category == "musings" -%}
        <span class="post-meta"> &raquo; </span>
        <a style="color:var(--main-subtitle-color);font-size:0.85rem;" href="{{site.url}}{{post.url}}">{{ post.subtitle }}</a>
      {%- endif -%}
    </span>
    <span class="post-meta" style="display: inline; color:var(--main-subtitle-color);font-size:0.8rem">
      &raquo; {% capture category_name %}{{ post.category }}{% endcapture %}<a style="white-space: nowrap; color: var(--main-subtitle-color);" href="{{site.url}}/category/{{ category_name }}"> <i class="fa-regular fa-folder-open" style="color: var(--main-subtitle-color); opacity: 0.80;"></i> {{ category_name }}</a>
      &raquo; <span style="white-space: nowrap;"> {{ post.date | date: "%Y-%m-%d" }}</span>
      &raquo; <span style="white-space: nowrap;"> {% assign words = post.content | strip_html | number_of_words %}
      {{ words | divided_by:200 | at_most:25 }} min</span>
    </span>
{% endfor %}