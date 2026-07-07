---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order. 
nav: true
nav_order: 4
---

<span>
  &#42; denotes a theory paper (authors are listed in <b>alphabetical order</b> in theory papers, following the tradition of the theory community of computer science).
</span>
{% include bib_search.liquid %}

<div class="publications">

<h1>Journals</h1>
{% bibliography -f journals %}

<h1>Conferences (peer reviewed)</h1>
{% bibliography -f conferences %}

<h1>Theses</h1>
<p>
  <strong>2026 ACM SIGEVO Best Dissertation Award (Honorable Mention).</strong>
</p>
{% bibliography -f theses %}

</div>
