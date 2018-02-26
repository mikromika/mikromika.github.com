---
layout: home
title: list of hobbies
---
<center><h2> <strong> {{ page.title | capitalize }} </strong></h2> </center><hr>

{% for post in site.categories.cv %}
 <li>   <span>{{ post.date | date_to_string }}</span>
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
 </li>
{% endfor %}
