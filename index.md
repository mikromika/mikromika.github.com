---
layout: home
title: Home
---

<div style="margin-left:1px">


  <div class="w3-container w3-blue">
    <h1>Mikromike's Page Header from index MD-file</h1>
    </div>

    {% for post in site.posts %}
    <div class="post">
    <a href="{{ post.url }}"<h2>{{ post.title }} </h2></a><br>
    <ul class="metadata">
      <li class="date"> {{ post.date | date_to_string }} </li>
      <li class="tags">
            {% for tag in post.tags %}
            <span class="label label-primary">{{ tag }}</span>
            {% endfor %}
          </li>
      </ul>
    </div>

    {% endfor %}



    </div>
    <center> End of index-md </center>
<hr>   
</div>
