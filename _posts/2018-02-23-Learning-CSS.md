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
Introduction to CSS

three ways to attach CSS inside HTML

## External CSS
<ul>    
          <li>
          A separete CSS local file with a .css file extension
          </li>
          <li>
          Always referenced within the <head> inside html 5
          </li>
          <li>
          Uses the <link> ant two attributes, rel and href
          </li>

        '''

              <link rel="stylesheet" href="stylesheet.css">

        '''
         HTML 5 style
        '''

            <link rel="stylesheet" type="text/css" href="stylesheet.css">

        '''
          XHTML style  
</ul>

## Inline CSS
<ul>  
      <li>
          Inline CSS is addesd using style attribute
      </li>
          Inline CSS is addesd using style attribute
        <li>
  '''

     <p style="color: blue;"> This text is blue.</p>
     
      '''
        </li>
        <li>
        </li>

</ul>

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


<center> <h2> Reference link list </h2>


<ul>
<li>  [ https://travis-ci.org/ ]( https://travis-ci.org/ ) </li>

<!-- <li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li>
<li> [  ](  ) </li> -->
</ul>
</center>
<!--more-->
This text is after more line
