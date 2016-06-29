---
layout: page
title: MWFrost.com
tagline: Analysis and Communication
---
{% include JB/setup %}

<div class="row">
<!--  <div class="span1"> -->
<!--  </div>  -->
  <div class="col-md-6">
    <h3>Projects</h3>
    <article class="markdown-body entry-content" itemprop="mainContentOfPage">
    <h4><a href="/ZoomSync.html">Zoom Sync</a> </h4>
    <p>View two maps of different places at a common scale</p>
    <img src="/assets/zoomsync.png" alt="Screenshot of two maps displayed side by side">
    <h4><a href="https://mwfrost.com/insurance_estimator/insurance_angular.html">Monte Carlo analysis for household health insurance costs</a> </h4>
    <p>Compare the costs of different health insurance plans across hundreds of scenarios</p>
      <img src="/assets/insurance.png" alt="Insurance Cost Distribution">
      <p><a href="https://github.com/mwfrost/insurance_estimator">Source code here.</a></p>
    <h4><a href="https://github.com/mwfrost/MSHA">Analysis of US mine safety data</a> </h4>
    <p>Using R and python to examine a large file of mine inspection records</p>
    <img src="/assets/msha.png" alt="Experimental mine safety analysis">
    <h4><a href="https://github.com/mwfrost/Energy_Storage_Valuation">An R implementation of EPRI's Energy Storage Valuation Primer </a></h4>
    <p>A white paper used randomly generated scenarios to evaluate the viability of an energy storage project. I rewrote the method in R.</p>
        <img src="/assets/epri.png" alt="EPRI analysis">

    </article>
  </div>
  <div class="col-md-6">
      <h3>Presentations</h3>
      <h4><a href="/r_slides/">&ldquo;Stop Clicking, Start Typing:&rdquo; an introduction to scripted analysis</a></h4>
      <a href="/r_slides/"><img src="/assets/slide_title.png" alt="Title Slide from R Tutorial"></a>
      <h3>My Resume</h3>
      <p>I am a professional data analyst serving the US federal government as a contractor, specializing in energy and environmental policy and economics. My resume is available as a pdf <a href="/assets/MattFrostResume.pdf">here.</a></p>
      <h3>My Public Key</h3>
      <p>Hosted at <a href="https://keybase.io/mattfrost">keybase.io/mattfrost</a> or <a href="/assets/mwfrost_public_key.txt">here.</a></p>
      <h3>Writing</h3>
      {% for post in site.posts %}
        <li><a href="{{ BASE_PATH }}{{ post.url }}.html">{{ post.title }}</a>&nbsp;{{ post.excerpt }}</li>
      {% endfor %}
    </div>
</div>
