---
layout: page
title: Post Archive
---

{% for post in site.posts %}
  * **[ {{ post.title }} ]({{ site.url }}{{ post.url }})** &raquo; [{% capture category_name %}{{ post.category }}{% endcapture %}
        <a style="white-space: nowrap; color: #303030" href="{{site.url}}/category/{{ category_name }}">{{ category_name }}</a>
    ] &raquo; {{ post.date | date: "%Y-%m-%d" }} &raquo; {% assign words = post.content | strip_html | number_of_words %}
    {{ words | divided_by:200 | at_most:25 }} mins
{% endfor %}