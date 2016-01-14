---
layout: page
title: Blog
permalink: /blog/
---
All of my blog posts are listed here, most recent first. 

Follow along via [RSS](../blogfeed.xml "Blog feed"), or on Medium.

<div class="page-content">
  <div class="mdl-grid">
    <ul>
      {% for post in site.categories.blog %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
