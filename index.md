---
title: Home
description: Official website for the Pickaway County Democratic Party - Ohio
hide_hero: true
hero_height: 0
layout: page
callouts: home_callouts
show_sidebar: true
show_latest_posts: false
show_candidates: true
---

## We are the Pickaway County Democratic party.
### Our mission is to work together to elect democracy-supporting, civic-minded individuals to local, state, and national offices.

<div class="box" style="background-color:#0044c9; color: white;">

<div class="has-text-centered is-size-3-mobile is-size-2-tablet is-size-1-desktop has-text-weight-bold">2022 General Election</div>
<div id="countdown" align="center" class="is-size-4-touch is-size-3-desktop"></div>
 <div class="level is-mobile">
  <div class="level-item has-text-centered">
    <div>
      <span class="cdtext" id="cdays">0</span>
      <p class="cdsubtext">Days</p>
    </div>
  </div>
  <div class="level-item has-text-centered">
    <div>
      <span class="cdtext" id="chours">0</span>
      <p class="cdsubtext">Hours</p>
    </div>
  </div>
  <div class="level-item has-text-centered">
    <div>
      <span class="cdtext" id="cminutes">0</span>
      <p class="cdsubtext">Minutes</p>
    </div>
  </div>
  <div class="level-item has-text-centered">
    <div>
      <span class="cdtext" id="cseconds">0</span>
      <p class="cdsubtext">Seconds</p>
    </div>
  </div>
 </div>
<script>
// Set the date we're counting down to
var pollsopen = new Date("2022-11-08T11:30:00Z").getTime();
var pollsclose = new Date("2022-11-09T00:30:00Z").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = Date.now();
        
  // If the count down is over, write some text 
  if ((pollsclose - now) < 0) {
    clearInterval(x);
    document.getElementById("countdown").innerHTML = "Polls Closed";
  } else {
  	if ((pollsopen - now) > 0) {
    	// Find the distance between now and the count down date
    	var timer = pollsopen - now;
 	 	// Time calculations for days, hours, minutes and seconds
  		document.getElementById("cdays").innerHTML = Math.floor(timer / (1000 * 60 * 60 * 24));
  		document.getElementById("chours").innerHTML = Math.floor((timer % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  		document.getElementById("cminutes").innerHTML = Math.floor((timer % (1000 * 60 * 60)) / (1000 * 60));
  		document.getElementById("cseconds").innerHTML = Math.floor((timer % (1000 * 60)) / 1000);  
  		// Output the result in an element with id="countdown"
  		document.getElementById("countdown").innerHTML = "Polls open in:<br>";
    } else {
      	// Find the distance between now and the count down date
  		var timer = pollsclose - now;
// Time calculations for days, hours, minutes and seconds
		document.getElementById("cdays").innerHTML = "0";
  		document.getElementById("chours").innerHTML = Math.floor((timer % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  		document.getElementById("cminutes").innerHTML = Math.floor((timer % (1000 * 60 * 60)) / (1000 * 60));
  		document.getElementById("cseconds").innerHTML = Math.floor((timer % (1000 * 60)) / 1000);  
  		// Output the result in an element with id="countdown"
  		document.getElementById("countdown").innerHTML = "Polls close in:<br>";
    }
  }
}, 1000);
</script>
<p class="has-text-centered is-size-7">*Timer is only as accurate as your device time</p>
</div>
<div class="buttons are-medium are-responsive is-centered">
  <a class="button is-link" href="https://lookup.boe.ohio.gov/vtrapp/pickaway/vtrlookup.aspx#">Check Voter Registration</a>
  <a class="button is-link" href="https://www.boe.ohio.gov/pickaway/voter-registration-information/how-to-register/">Register to Vote</a>
</div>

<h3>Registration deadlines</h3>
<ul>
  <li><a href="https://olvr.ohiosos.gov/">Online:</a> Oct 11</li>
  <li><a href="https://www.boe.ohio.gov/pickaway/election-info/registration-deadlines/">In-person</a> at Board of Elections: Oct 11</li>
  <li><a href="https://www.ohiosos.gov/publications/#vrf">By mail</a> (postmarked by): Oct 11</li>
</ul>
<h3>Absentee ballot deadlines</h3>
<ul>
  <li><a href="https://www.boe.ohio.gov/pickaway/absentee-information/absentee-voting/">Request Ballot</a> (received by): Nov 5</li>
  <li><a href="https://www.boe.ohio.gov/pickaway/absentee-information/absentee-voting/">Return ballot by mail</a> (postmarked by): Nov 7</li>
  <li><a href="https://www.boe.ohio.gov/pickaway/absentee-information/absentee-voting/">Return ballot in person:</a> Nov 8</li>
</ul>
<h3>Voting deadlines</h3>
<ul>
  <li><a href="https://www.boe.ohio.gov/pickaway/c/upload/Election_hours.pdf">Early Voting:</a> Oct 12 - Nov 7</li>
  <li><a href="https://lookup.boe.ohio.gov/vtrapp/pickaway/vtrlookup.aspx#">In-person:</a> Nov 8</li>
</ul>

