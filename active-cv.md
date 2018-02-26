---
layout: home
title: Home
---
<div style="margin-left:1px">
  <div class="w3-container w3-blue">
    <h3 class="w3-text-black"><center>Mikromike's Page Header from index MD-file </center></h3>
    <hr><br>



{% for post in site.categories.cv %}
 <li>   <span>{{ post.date | date_to_string }}</span>
              &nbsp; <a href="{{ post.url }}"> {{ post.title }}</a>
 </li>
{% endfor %}



    <center> End of index-md </center>
<hr>

</div>
