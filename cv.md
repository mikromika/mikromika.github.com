---
layout: home
title: Active CV
---
<center> <h2> <strong> {{ page.title | capitalize }} </strong> </h2> </center>
<hr>
  <div class="w3-container w3-blue">
{% for post in site.categories.cv %}
 <li><h2>  <span>{{ post.date | date_to_string }}</span> </h2>
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
 </li>
{% endfor %}
<hr>
</div>
