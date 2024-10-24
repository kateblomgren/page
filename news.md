---
layout: page
title: "news"
---
<div class="row g-5 mb-5">
  
    {% for post in site.posts %}
      <p><a href="{{ site.github.url }}/{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}</p>
    {% endfor %}
  
</div>