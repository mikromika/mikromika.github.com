---
layout: home
title: Home
---
<div style="margin-left:1px">


<div class="post">

    {% for post in site.posts %}
          <a href="{{ post.url }}"> <h2>{{ post.title }}</h2> </a>
          <p>{{ post.date | date_to_string }}</p>
Post has Tagged:
        {% for tag in post.tags %}
          <span class="label label-primary"> {{ tag }}</span>
        {% endfor %}
   {% endfor %}

</div>

    <center> End of index-md file </center>
<hr>

</div>
