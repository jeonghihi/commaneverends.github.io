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
<font color="red"> {{ member.date }} </font> / <font color="yellow"> {{ member.title }} </font> / <font color="gray"> {{ member.link }} </font>
  </li>
{% endfor %}
</ul>
</details>
