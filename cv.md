---
layout: home
title: Active CV
---
<center><h2> <strong> {{ page.title | capitalize }} </strong></h2> </center><hr>

{% for post in site.categories.cv %}
 <li><h2>  <span>{{ post.date | date_to_string }} </h2></span>
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
 </li>
{% endfor %}
