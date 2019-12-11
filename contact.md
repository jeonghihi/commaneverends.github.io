---
title: /contact
layout: page
permalink: /contact
---

# Get in touch?

<form>
  <input type="text" id="name" name="name" placeholder="name:" autocomplete="off">
  <input type="text" id="email" name="email" placeholder="email:" autocomplete="off">
  <textarea rows="5" id="message" name="message" placeholder="message:" autocomplete="off"></textarea>
  <input type="submit" value="[ submit ]">
</form>

new form style-popup5
  
<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<div class ="contact_form">
<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycby9UD1hY-kS3WPUskcd0KyCynxdzIQlyUnAYWgEVPKHknZYrOA/exec" target="after" onsubmit="close()">
<form>
  <input type="text" id="name" name="name" placeholder="name:" autocomplete="off">
  <input type="text" id="email" name="email" placeholder="email:" autocomplete="off">
  <textarea rows="5" id="message" name="message" placeholder="message:" autocomplete="off"></textarea>
  <input type="submit" value="[ submit ]" onclick="displayThanks()">  
</form>
<iframe id="after" name="after" frameborder="0" onmousewheel="" width="100%" height="10" style="background: transparent; border: none;">
</iframe>
</div>

<div style="display:none" class="thanks_message">
<span id="span_thanks"> Thank you for contacting us ! </span>
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
