<ul>
{% for member in site.data.musicform %}
  <li>
      {{ member.item }} {{ member.genre }}
  </li>
{% endfor %}
</ul>
