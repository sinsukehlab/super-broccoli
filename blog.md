---
layout: default
title: Blog
---
# Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date_to_string }} by {{ post.author }}
{% endfor %}
