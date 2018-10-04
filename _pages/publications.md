---
title: "HLi Lab - Publications"
layout: gridlay
excerpt: "HLi Lab -- Publications"
sitemap: false
permalink: /publications/
---


# Publications & Presentations

## Selected publications

(For a full list of publications, see [Google Scholar](https://scholar.google.com/citations?user=HQv0p0kAAAAJ))

<ul>
{% for publi in site.data.publist %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>.</li>
{% endfor %}
</ul>
