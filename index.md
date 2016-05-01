---
layout: page
title: 叩首问路，码梦为生
tagline:
---
{% include JB/setup %}

幸福可以无限靠近，无法彻底到达.<br>
不挣扎不绝望不算青春

## PHP 

<!-- In `_config.yml` remember to specify your own data: -->
    
    title : Renf's Blog = alltosun
    
    author :
      name : renf
      email : renf_cd@163.com

<!-- #The theme should reference these variables whenever needed.-->
    
<!-- ## Sample Posts

#This blog contains sample posts which help stage pages and blog data.
#When you don't need the samples anymore just delete the `_posts/core-samples` folder.

#    $ rm -rf _posts/core-samples
-->
<!-- Here's a sample "posts list". -->

### 文章列表
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<!-- ## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
-->


