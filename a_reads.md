---
layout: page
title: /articles
permalink: /articles/
---


- This is a list of articles.

<i class="fas fa-map-marked-alt"></i>
- Click *articles to read* below to see details. (in alphabetical order)

<details>
<summary> articles to read </summary>
<ul>
  {% for member in site.data.articles %}
  <li>
<font color="green"> {{ member.date }} </font> / <font color="blue"> <a href = "{{ member.link }}" target="_blank"> {{ member.title }} </a> </font>
  </li>
{% endfor %}
</ul>
</details>
