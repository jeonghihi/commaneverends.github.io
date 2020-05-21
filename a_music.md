---
layout: page
title: /music
permalink: /music/
---

# music, neverends 


We are making an archive of musicians/sound artists who identifies as XX.

Let us know your fav songs, musicians, any kinds of sound artists. 

---
<font color="red"> Feel free to share your fav music, to make this archive more diverse and interesting. </font> 

<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycbz-6TLQGMxloAJtH1JQ-w1hf4GouwAZisDs2gBN7RUJ1uYw2Rg/exec" target="after" onsubmit="close()">
  
<form>
  <input type="text" id="name" name="name" placeholder="artist name:" autocomplete="off">
  <input type="text" id="genre" name="genre" placeholder="genre: e.g. rock, electronic, rap, hiphop, classic, jazz, other" autocomplete="off">
  <input type="text" id="email" name="subscription" placeholder="If you want further updates: write your email address here" autocomplete="off">  
  <input type="submit" value="[ submit ]" onclick="displayThanks()">  
 
</form>

<iframe id="after" name="after" frameborder="0" onmousewheel="" width="100%" height="0.1" style="background: transparent; border: none;">
</iframe>

<div style="display:none" class="thanks_message">
<span id="span_thanks"> Thanks for contacting us. We will contact you soon! </span>
</div>

<script>
function close() {
    document.querySelector('#after').addEventListener('load', function() {
        window.close();
    });
  }
function displayThanks() {
   var span_Text = document.getElementById("span_thanks").innerText;
   alert (span_Text);
}
</script>

---


If you want to listen to our selection of their music, follow us on spotify/soundcloud. 

You can also click below "music, neverends" to see the current archive.

<details>
<summary> "music, neverends" </summary>
  
<h3><font color="white"> artist </font> / <font color="white"> genre </font>(in alphabetical order) <p>

<ul>
{% for member in site.data.musicform %}
  <li>
      <font color="red">{{ member.item }}</font> <font color="yellow">{{ member.genre }}</font> 
  </li>
{% endfor %}
</ul>
  

</details>
