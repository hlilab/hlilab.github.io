---
title: "HLi Lab - Publications"
layout: gridlay
excerpt: "HLi Lab -- Publications"
sitemap: false
permalink: /publications/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
<script async type="text/javascript" src="https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js"></script>

# Selected Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=HQv0p0kAAAAJ); star for equal contribution; <sup>&#8224;</sup> for corresponding authors; bold fontface for lab members/interns)

<ul>
{% for publi in site.data.recentpub %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>.
<table class="shadow-none"><tr style="vertical-align:top">
<td><span class="__dimensions_badge_embed__" data-pmid="{{ publi.pmid }}" data-legend="never" data-style="small_rectangle">&nbsp;</span></td>
<td><div data-badge-type="2" data-pmid="{{ publi.pmid }}" data-condensed="true" class="altmetric-embed shadow-none">&nbsp;</div></td>
<td><div class="shadow-none"><a href="https://pubmed.ncbi.nlm.nih.gov/33526886"><img src="https://img.shields.io/badge/PMID-33526886-blue"/></a></div></td>
</tr></table>
</li>
{% endfor %}
</ul>
