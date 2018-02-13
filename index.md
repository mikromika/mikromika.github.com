---
layout: home
title: Home
---
<div style="margin-left:1px">

  <div class="w3-container w3-blue">

    <h1>Mikromike's Page Header from index MD-file</h1>

    {% for post in site.posts %}
      <div class="post">
      <a href="{{ post.url }}"<h2>{{ post.title }} </h2></a><br>
        </div>
      {% endfor %}
        </div>
    <center> End of index-md </center>
<hr>   
</div>
