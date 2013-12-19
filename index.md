---
layout: page
title: MWFrost.com
tagline: Matt Frost
---
{% include JB/setup %}



<div class="row">
<div class="span6">
<h3>Projects</h3>
<p>include follows</p>
{% include projects.md %}
</div>
  <div class="span6">
  <h3>Writing</h3>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </div>
</div>
