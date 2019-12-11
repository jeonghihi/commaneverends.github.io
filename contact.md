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

new form style-popup
  
<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycby9UD1hY-kS3WPUskcd0KyCynxdzIQlyUnAYWgEVPKHknZYrOA/exec" target="after" onsubmit="close()">
<form>
  <input type="text" id="name" name="name" placeholder="name:" autocomplete="off">
  <input type="text" id="email" name="email" placeholder="email:" autocomplete="off">
  <textarea rows="5" id="message" name="message" placeholder="message:" autocomplete="off"></textarea>
  <input type="submit" value="[ submit ]">  
</form>
<iframe id="after" name="after"></iframe>
<script>
function close() {
    document.querySelector('#after').addEventListener('load', function() {
        window.close();
    });
}
</script>
