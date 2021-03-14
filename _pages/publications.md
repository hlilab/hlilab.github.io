---
title: "HLi Lab - Publications"
layout: gridlay
excerpt: "HLi Lab -- Publications"
sitemap: false
permalink: /publications/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

# Selected Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=HQv0p0kAAAAJ); star for equal contribution; <sup>&#8224;</sup> for corresponding authors; bold fontface for lab members/interns)

<ul>
{% for publi in site.data.recentpub %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>.
[PMID: <a href="https://www.ncbi.nlm.nih.gov/pubmed/{{ publi.pmid }}">{{ publi.pmid }}</a>]
[<a href="https://badge.dimensions.ai/details/pmid/{{ publi.pmid }}">Citations</a>]
</li>
{% endfor %}
</ul>
