---
layout: post-list
title: Operation: FemForEveryone
excerpt: "A List of Posts"
comments: false
---
{% for post in site.categories.FemForEveryone %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
