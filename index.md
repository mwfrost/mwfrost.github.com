---
layout: page
title: MWFrost.com
tagline: Matt Frost
---
{% include JB/setup %}



<div class="row">
<div class="span6">
<h3>Projects</h3>

[Ongoing analysis of US mine safety data](https://github.com/mwfrost/MSHA)

[Monte Carlo analysis for households](https://github.com/mwfrost/insurance_estimator)

[An R implementation of EPRI's Energy Storage Valuation Primer ](https://github.com/mwfrost/Energy_Storage_Valuation)

</div>
  <div class="span6">
  <h3>Writing</h3>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </div>
</div>
