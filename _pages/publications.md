---
title: "HLi Lab - Publications"
layout: gridlay
excerpt: "HLi Lab -- Publications"
sitemap: false
permalink: /publications/
---

# Selected Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=HQv0p0kAAAAJ); star for equal contribution; <sup>&#8224;</sup> for corresponding authors; bold fontface for lab members/interns)

<ul>
{% for publi in site.data.recentpub %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>. {{ publi.cite }}</li>
{% endfor %}
</ul>
