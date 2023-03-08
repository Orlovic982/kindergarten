---
layout: default
title: "Home"
---
  <nav>
     {% for item in site.data.navbar %}
      <a href="{{item.link}}">{{ item.name }}</a>    
      {% endfor %}  
    </nav>

Start developing your Jekyll website.
<div class="text-blue-500">
  Text red 500
</div>
<ol>   
     {% for post in site.posts %}
      <li>{{ post.title }}</li>    
      {% endfor %}  
</ol>

