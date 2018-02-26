---
layout: post
title: CSS - content do not show correctly yet.
date: 2018-02-23
tag: [Learning, Css, Getting started]
twitter: mikromike
published: true
author: mikromike
category: Learning
---
Introduction to CSS <br>

three ways to attach CSS inside HTML 5

{% raw %}
Hello, my name is {{name}}.
{% endraw %}

1. ## External CSS
  - A separete CSS local file with a .css file extension  
  - Always referenced within the <head> inside html 5   
  - Uses the <link> ant two attributes, rel and href   

  HTML 5 style <br>
'''css

<link rel="stylesheet" href="stylesheet.css">

'''
  XHTML style   <br>
'''css
<link rel="stylesheet" type="text/css" href="stylesheet.css">

'''

2.
## Inline CSS
<ul>  
      <li>
          Inline CSS is addesd using style attribute
      </li>
          Inline CSS is addesd using style attribute
        <li>
'''css

     <p style="color: blue;"> This text is blue.</p>

'''
        </li>
        <li>
        </li>

</ul>

3.
## Internal CSS
<ul>
      <li>  
        Internal CSS uses the <style> tag, included in the <head> element.
      </li>
      <li>
        <p> Internal CSS will overwrites external CSS, only if it's added after
        the external stylesheet. </p>
      </li>
'''html
       <head>
        <link rel="stylesheet" href="external.css">
          <style>
            p {
              color: blue;
              )
          </style>
      </head>
'''
</ul>

<!--more-->
Reference links
[ http://gs.statcounter.com ]( http://gs.statcounter.com )  <br>
[ http://caniuse.com/usage-table ]( http://caniuse.com/usage-table ) <br>
[ https://goo.gl/gNmaVD ]( end of older IE Support ) <br>
