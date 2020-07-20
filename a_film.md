---
layout: page
title: /film
permalink: /film/
---

<h1>film, neverends</h1>

Here you can find female* directors and some of their masterpieces.

<details>
<summary> "film, neverends" </summary>
  table-ver2-test2
  <iframe style="border-style: none;" src="https://commaneverends.github.io/tablemaker/index.html" height="300" width="600" frameBorder="0"></iframe>
  
  table-ver1
  <h3><font color="white"> director </font> / <font color="white"> movie </font>  / <font color="white"> year </font> (in alphabetical order) </h3>
    <ul>
    {% for member in site.data.filmform %}
      <li>
          <font color="red">{{ member.item }}</font> <font color="yellow">{{ member.movie }}</font> <font color="green">{{ member.year }}</font> 
      </li>
    {% endfor %}
    </ul>
</details>


---


---

Additionally we created a global map to emphasize the diversity of female* film directors.
_map_


---


<font color="red"> Send us your fav films made by female* directors. </font> 

<script data-cfasync="false" type="text/javascript" src="form-submission-handler.js"></script>

<form class="gform" method="POST" id="car_request_form" role="form" action="https://script.google.com/macros/s/AKfycbw4uqE9OpRTnm_7eIdmPS7VLADGdQI6l6Tn0ueX/exec" target="after" onsubmit="close()">
  
<form>
  <input type="text" id="name" name="name" placeholder="director name:" autocomplete="off">
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


---  



# other interesting links
