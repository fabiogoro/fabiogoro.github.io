---
layout: default
title: Fabio Gorodscy // Github Page
---

# Hey, I'm Fabio Gorodscy.

I'm a programmer and student of computer science. [More...](/about)

# Latest posts

{% for post in site.posts %}
* {{ post.date | date_to_string }} » [{{ post.title }}]({{ post.url }})
{% endfor %}
