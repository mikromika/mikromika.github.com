---
layout: home
title: Home
---
<div style="margin-left:1px">
  <div class="w3-container w3-white">
    <h1 class="w3-text-black"><center>Mikromike's Page Header from index MD-file </center></h1>
<div class="post">
  <li>
    {% for post in site.posts %}
      <a href="{{ post.url }}"> <h2>{{ post.title }}</h2> </a>
        <p>{{ post.date | date_to_string }}</p>
    {% endfor %}
  </li>


          {% for tag in post.tags %}
          <span class="label label-primary">{{ tag }}</span>
          {% endfor %}

</div>
    <center> End of index-md </center>
<hr>   
</div>
