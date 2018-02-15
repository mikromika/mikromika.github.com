---
layout: home
title: list of hobbies
---
<center> <strong> {{ page.title | capitalize }} </strong> </center><hr>

{% for post in site.categories.hobby %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
