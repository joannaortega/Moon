---
layout: post-list
title: Operation: Literary Citizenship
excerpt: "A List of Posts"
comments: false
---
{% for post in site.categories.LitCitizenship %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<figure> {% if class != "" %}class="{{ class }}"{% endif %}>
    {% for image in images %}
    <a href="{{ image }}"><img src="{{ image }}" alt=""></a>
    {% endfor %}
    <figcaption>{{ caption }}</figcaption>
</figure>
