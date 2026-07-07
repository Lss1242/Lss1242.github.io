---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order. 
nav: true
nav_order: 4
---

<span>
  (αβ) indicates alphabetical author order. &#42; indicates equal contribution.
</span>
{% include bib_search.liquid %}

<div class="publications">

<h1>Journals</h1>
{% bibliography -f journals %}

<h1>Conferences</h1>
{% bibliography -f conferences %}

<h1>Theses</h1>
{% bibliography -f theses %}

</div>
