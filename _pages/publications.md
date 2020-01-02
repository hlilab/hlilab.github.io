---
title: "HLi Lab - Publications"
layout: gridlay
excerpt: "HLi Lab -- Publications"
sitemap: false
permalink: /publications/
---

# Recent Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=HQv0p0kAAAAJ))

<ul>
{% for publi in site.data.recentpub %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>.</li>
{% endfor %}
</ul>
