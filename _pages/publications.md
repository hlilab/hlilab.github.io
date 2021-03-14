---
title: "HLi Lab - Publications"
layout: gridlay
excerpt: "HLi Lab -- Publications"
sitemap: false
permalink: /publications/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>
<script type="text/javascript" src="https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js"></script>

# Selected Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=HQv0p0kAAAAJ); star for equal contribution; <sup>&#8224;</sup> for corresponding authors; bold fontface for lab members/interns)

<ul>
{% for publi in site.data.recentpub %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>.
<table><tr style="vertical-align:top">
<td>Citations:&nbsp;</td>
<td><span class="__dimensions_badge_embed__" data-pmid="{{ publi.pmid }}" data-legend="never" data-style="small_rectangle">&nbsp;</span></td>
<td><span data-badge-type="4" data-pmid="{{ publi.pmid }}" data-condensed="true" data-hide-no-mentions="true" class="altmetric-embed">&nbsp;</span></td>
</tr></table>
</li>
{% endfor %}
</ul>
