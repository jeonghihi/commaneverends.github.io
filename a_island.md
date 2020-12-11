---
layout: page
title: /island
permalink: /island/
---
<style>
   
h2 {color:#4C39CA; font-size: 24px;
    }
    
.bodycontents {background-color: #F51D0057; 

    }
.maintext {margin: 10px 10px 20px 10px;}
    
</style>
  
  
<div class="bodycontents">
    
    <div class="maintext">
<h2> island, neverends </h2>
Here you can find a list of events, happening now and then. Let's stay in touch 
</br>

- event name / dates / : event <span style="font-weight: bold; font-style: italic;"><a href="commaneverends.github.io" target="_blank"> link (click to open this link) </a></span>.

</div>

</div>

---
         
<font color='yellow'> Send us your events if you are planning to host something in the future. </font> 

<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycbxZYxmzxIl79dR-rQUCo9aGwTDu6YRiD4gfXFWv5w/exec" target="after" onsubmit="close()"> //need to change form link for events//
  
<form>
  <input type="text" id="name" name="eventname" placeholder="Name of the event:" autocomplete="off">
  <input type="text" id="title" name="eventlink" placeholder="Link to the event:" autocomplete="off">
  <input type="text" id="genre" name="eventgenre" placeholder="Genre of the event: e.g. feminism, queer, social, business, sports, other" autocomplete="off">
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
