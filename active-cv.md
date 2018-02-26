---
layout: home
title: Home
---
<div style="margin-left:1px">
  <div class="w3-container w3-white">
    <h3 class="w3-text-black"><center>Mikromike's Page Header from index MD-file </center></h3>
    <hr><br>

<div class="post">

  {% for post in site.posts.cv %}
          <a href="{{ post.url }}"> <h2>{{ post.title }}</h2> </a>
          <p>{{ post.date | date_to_string }}</p>
Post has Tagged:
        {% for tag in post.tags %}
          <span class="label label-primary"> {{ tag }}</span>
        {% endfor %}
   {% endfor %}

</div>

    <center> End of index-md </center>
<hr>

</div>
