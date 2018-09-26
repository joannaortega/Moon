---
layout: post-layout
title: Classified: Random Thoughts
excerpt: "I'll fix this later"
comments: false
---
{% for post in site.categories.RandomThoughts %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
