---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<p><sup>#</sup> Equal contribution (co-first authors); <sup>✉︎</sup> Corresponding author(s).</p>

<div class="publications">

  <h2>First-author</h2>

  {% bibliography --query @*[authorship=first] %}

  <h2 style="margin-top: 3rem;">Collaborative</h2>

  {% bibliography --query @*[authorship=collaborative] %}

</div>
