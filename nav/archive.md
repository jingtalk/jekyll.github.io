---
layout: page
title: archive
permalink: /archive/
header-img: "images/blog/jing-home.jpg"
---

### Blogs
<hr>

{% for post in site.posts %}
<div class="post-preview">
    <font color="blue">[{{ post.date | date: "%B %-d, %Y" }}]  </font> 
     <a target="_blank" href="{{ post.url | prepend: site.baseurl }}"> {{ post.title }}  </a> 
</div>
<hr>
{% endfor %}
