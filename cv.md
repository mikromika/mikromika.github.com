---
layout: home
title: Active CV
---
<center> <h3> <strong> {{ page.title | capitalize }} </strong> </h2> </center>
<br>
<hr>
  <div class="w3-container w3-blue">
  <h2>
{% for post in site.categories.cv %}
 <li>  <span>{{ post.date | date_to_string }}</span>  
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
  </li>
{% endfor %}
</h3>
</div>
