---
layout: page
title: MWFrost.com
tagline: Matt Frost's personal projects
---
{% include JB/setup %}

<div class="row">
  <div class="span1">
  </div>
    <div class="span5">
    <h3>Projects</h3>
    <article class="markdown-body entry-content" itemprop="mainContentOfPage">

    <h4><a href="https://github.com/mwfrost/MSHA">Ongoing analysis of US mine safety data</a> </h4>
    <img src="/assets/msha.png" alt="Experimental mine safety analysis">
    <h4><a href="https://github.com/mwfrost/insurance_estimator">Monte Carlo analysis for household health care costs</a> </h4>
    <img src="/assets/insurance.png" alt="Insurance Cost Distribution">
    <h4><a href="https://github.com/mwfrost/Energy_Storage_Valuation">An R implementation of EPRI's Energy Storage Valuation Primer </a></h4>
        <img src="/assets/epri.png" alt="EPRI analysis">

    </article>
    </div>
      <div class="span5">
      <h3>Presentations</h3>
      <h4><a href="/r_slides/">&ldquo;Stop Clicking, Start Typing:&rdquo; an introduction to scripted analysis</a></h4>
      <a href="/r_slides/"><img src="/assets/slide_title.png" alt="Title Slide from R Tutorial"></a>
      <h3>My Resume</h3>
      <p>Available as a pdf <a href="/assets/MattFrostResume.pdf">here.</a></p>
      <h3>Writing</h3>
      {% for post in site.posts %}
        <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>&nbsp;{{ post.excerpt }}</li>
      {% endfor %}
      </div>
</div>
