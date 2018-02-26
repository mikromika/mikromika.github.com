---
layout: home
title: Home
---
<div style="margin-left:1px">
  <div class="w3-container w3-blue">


{% for post in site.categories.cv %}
 <li>   <span>{{ post.date | date_to_string }}</span>
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
 </li>
{% endfor %}



    <center> End of index-md </center>
<hr>

</div>
</div>
