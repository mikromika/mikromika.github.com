---
layout: home
title: Home
---

<div style="margin-left:1px">


  <div class="w3-container w3-blue">
    <h1>Mikromike's Page Header from index MD-file</h1>
    </div>

    <div class="w3-container">
        <div class="w3-content">
        {% assign image_files = site.static_files | where: "image", true %}
          {% for myimage in image_files %}
            {{ myimage.path }}
              {% endfor %}
        </div>

    </div>
<hr>   
</div>
