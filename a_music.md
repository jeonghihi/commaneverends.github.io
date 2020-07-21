---
layout: page
title: /music
permalink: /music/
---

# music, neverends
Here you can find female* musicians/sound artists.
&nbsp;
Click the logo below to see the current archive.

<details>
  
<summary> "music, neverends" </summary>
  <h3><font color="#cdcbcb"> artist </font> / <font color="white"> genre </font>(in alphabetical order)</h3>
    <ul>
    {% for member in site.data.musicform %}
      <li>
          <font color="red">{{ member.item }}</font> <font color="yellow">{{ member.genre }}</font> 
      </li>
    {% endfor %}
    </ul>

</details>

<details>
  
<summary> "music, neverends (ver2)" </summary>
  <h3> table-ver2 </h3>
  <iframe style="border-style: none;" src="https://commaneverends.github.io/table_music/index.html" height="300" width="600" frameBorder="0" allowtransparency="true"></iframe> 
</details>

---


 
<font color="red"> Send us your fav songs, musicians, any kinds of sound artists. </font> 

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
<span id="span_thanks"> Thanks for your support. See you again! </span>
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


\
---
\
If you want to listen to our selection of their music, follow us on spotify/soundcloud. (_soundcloud link_spotifyl link)


---


\
_other interesting links_
