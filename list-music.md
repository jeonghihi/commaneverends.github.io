<ul>
{% for member in site.data.musicform %}
  <li>
      <font color="red">{{ member.item }}</font> <font color="blue">{{ member.genre }}</font> 
  </li>
{% endfor %}
</ul>
