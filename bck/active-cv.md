---
layout: home
title: Home
---
<br>
  <div class="w3-container w3-blue">
{% for post in site.categories.cv %}
 <li style="margin-left:1px margin-top:10px">   <span style="margin-left:18px margin-top:16px">{{ post.date | date_to_string }}</span>
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
 </li>
{% endfor %}
    <center> End of index-md </center>
<hr>
</div>
