---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

Papers and preprints, grouped by research area. Manuscripts under review are labeled below.

{% include bib_search.liquid %}

<div class="publications">

<h2>Robot Learning &amp; Generative Modeling</h2>

{% bibliography --query @*[research_area=robotics]* %}

<h2>Learning, Optimization &amp; Theory</h2>

{% bibliography --query @*[research_area=theory]* %}

</div>
