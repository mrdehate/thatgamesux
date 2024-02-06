---
layout: blog
title: "The Archive"
---
Hi

{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> » <a href="thatgamesux/{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
{% endfor %}
