---
layout: page
title: "The Archive"
---
Do you want every post on this site in a big bulleted list? Great news, you're in the right spot. 

<ul class="archive-list">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> » <a href="/thatgamesux{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
