<h3><font color="white"> artist </font> / <font color="white"> genre </font>(in alphabetical order) <p>

<ul>
{% for member in site.data.musicform %}
  <li>
      <font color="red">{{ member.item }}</font> <font color="yellow">{{ member.genre }}</font> 
  </li>
{% endfor %}
</ul>
