---
layout: page
title: Work
permalink: /projects/
---
<div class="page-content">
  <h4>Professional</h4>
	<ul>
	  {% for post in site.categories.professional %}
		<li>
		  <a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	  {% endfor %}
	</ul>
  <h4>Projects and Interests</h4>
	<ul>
	  {% for post in site.categories.sideproject %}
		<li>
		  <a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	  {% endfor %}
	</ul>
</div>
