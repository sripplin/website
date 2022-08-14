---
layout: page
title: Post Archive
---

{% for post in site.posts %}
  * [{% capture category_name %}{{ post.category }}{% endcapture %}
        <a style="white-space: nowrap; color: #303030" href="/category/{{ category_name }}">{{ category_name }}</a>
    ] &raquo; **[ {{ post.title }} ]({{ site.url }}{{ post.url }})** &raquo; {{ post.date | date_to_string }} &raquo; {% assign words = post.content | strip_html | number_of_words %}
    {{ words | divided_by:200 | at_most:25 }} mins
{% endfor %}