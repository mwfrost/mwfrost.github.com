---
layout: page
title: MWFrost.com
tagline: Matt Frost
---
{% include JB/setup %}



<div class="row">
<div class="span6">
<h3>Projects</h3>
<article class="markdown-body entry-content" itemprop="mainContentOfPage">

<p><a href="https://github.com/mwfrost/MSHA">Ongoing analysis of US mine safety data</a> </p>

<p><a href="https://github.com/mwfrost/insurance_estimator">Monte Carlo analysis for households</a> </p>

<p><a href="https://github.com/mwfrost/Energy_Storage_Valuation">An R implementation of EPRI's Energy Storage Valuation Primer </a></p>
</article>
</div>
  <div class="span6">
  <h3>Writing</h3>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </div>
</div>
