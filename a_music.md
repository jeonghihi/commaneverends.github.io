---
layout: page
title: /music
permalink: /music/
---

# this page will include the archive of musician/sound artists


Let us know your taste

<iframe src="https://airtable.com/embed/shr77TgVV45CeCx7Y?backgroundColor=yellow" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;" allowfullscreen=""></iframe>

---
new submission form

<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycbz-6TLQGMxloAJtH1JQ-w1hf4GouwAZisDs2gBN7RUJ1uYw2Rg/exec" target="after" onsubmit="close()">
  
<form>
  <input type="text" id="name" name="name" placeholder="name:" autocomplete="off">
  <input type="text" id="email" name="email" placeholder="email:" autocomplete="off">
  <textarea rows="4" id="message" name="message" placeholder="message:" autocomplete="off"></textarea>
  <input type="checkbox" id="checkbox-genre" name="checkbox-genre" placeholder="Rock-genre" checked />
 
  <input type="checkbox" id="checkbox-rock" name="checkbox" value="Rock" checked /> <label for="checkbox-rock">Rock2</label> 
  <input type="checkbox" id="checkbox-jazz" name="checkbox" value="Jazz" /> <label for="checkbox-jazz">Jazz</label> 
  <input type="checkbox" id="checkbox-electronic" name="checkbox" value="electronic" /> <label for="checkbox-electronic">Electronic</label> 
  <input type="checkbox" id="checkbox-other" name="checkboxes" value="other" checked /> <label for="checkboxes--other">Other</label>

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
