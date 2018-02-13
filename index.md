---
layout: home
title: Home
---
<div style="margin-left:1px">

  <div class="w3-container w3-blue">

    <h1>Mikromike's Page Header from index MD-file</h1>

    {% for post in site.posts %}
      <a href="{{ post.url }}">  </a>
        <h2>{{ post.title }}</h2>
        <p>{{ post.date | date_to_string }}</h2>
     
    {% endfor %}




    <center> End of index-md </center>
<hr>   
</div>
