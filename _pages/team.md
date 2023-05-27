---
title: "HLi Lab - Team"
layout: gridlay
excerpt: "HLi Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members


{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br/>

# Past Members

* [Yujie (York) Zhang](https://yuz682.github.io/) (2021-2023). HSPH master student &#8594; PhD student in UCSF
* [Li Song](https://www.linkedin.com/in/li-song-81201329) (2021-2022). Postdoc &#8594; Assistant professor in Dartmouth College
* [Haowen Zhang](https://zhanghaowen.com/) (2019-2022). Intern PhD student and collaborator in GaTech &#8594; Software engineer at Google
* Yaxin Yang (2021). Visiting undergraduate student in University of Rochester &#8594; PhD candidate in UIUC
* [Jiazhen (Jojo) Rong](https://www.linkedin.com/in/jiazhen-jojo-rong-3ab8b610b/) (2019-2021). DBMI master student &#8594; PhD candidate in UPenn
