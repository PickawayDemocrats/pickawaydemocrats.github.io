---
title: Home
description: Official website for the Pickaway County Democratic Party - Ohio
hide_hero: true
hero_height: 0
layout: page
callouts: home_callouts
show_sidebar: true
show_latest_posts: false
---


<style>
.horizontal-line {
    padding-top: 20px;
    border-top: 5px solid #1884B3; 
}
</style>
<div class="columns">
  <div class="column is-narrow">
	<figure class="image is-inline-block">
	<img src="/img/PCDPLogo256.png">
	</figure>
  </div>
  <div class="column">
<h2>We are the Pickaway County Democratic party.</h2>
	<p style="font-size:18px;color:black;font-family:verdana">Our mission is to work together to elect democracy-supporting, civic-minded individuals to local, state, and national offices.</p>
	<div class="buttons are-large are-responsive is-centered">
  <a class="button is-link" href="https://docs.google.com/forms/d/e/1FAIpQLSfQ10VB0RU24C72BI8LO9YG2gKFu1Bos6x86qeeTO_0jYmFvw/viewform?usp=sf_link">
  <span>Get Involved</span>
  </a>
  {% if site.contribute %}
  <a class="button is-link" href="{{ site.contribute}}">
    <span>Contribute </span>
  </a>
  {% endif %}
</div>
  </div>
</div>
<h2 class="title is-3 horizontal-line">March 19th Primary Election</h2>
Voting Early? Check the Board of Elections <a href="https://www.boe.ohio.gov/pickaway/c/upload/Election_hours.pdf"> early voting hours calendar</a>.
<div class="has-text-centered">
<figure class="image is-inline-block">
<img src="/img/65_CountyPartyJudicialEndorsement.png">
</figure>
</div>
<h3>Endorsed Candidates</h3>
<div>
{% for level in site.data.candidates %} 
     {% for item in level %}
      	<p style="font-size:26px;color:black;font-family:verdana"><b>{{ item.name }}</b> - {{ item.office }}
	{% if item.web %}
	   <a href="{{ item.web }}" title="Web">
		<i class="fa fa-solid fa-globe"></i>
	      <span class="sr-only">Web</span>
	   </a>
	{% endif %}
	{% if item.facebook %}
	   <a style="padding-left:10px;" href="https://www.facebook.com/{{ item.facebook }}" title="Facebook">
	     	<i class="fab fa-facebook"></i>
	      <span class="sr-only">Facebook</span>
	   </a>
	{% endif %}
	{% if item.twitter %}
	    <a style="padding-left:10px;" href="https://www.twitter.com/{{ item.twitter }}" title="Twitter">
	     	<i class="fab fa-twitter"></i>
	      <span class="sr-only">Twitter</span>
	   </a>
	{% endif %}
	{% if item.instagram %}
	    <a style="padding-left:10px;" href="https://www.instagram.com/{{ item.instagram }}" title="Instagram">
	     	<i class="fab fa-instagram"></i>
	      <span class="sr-only">Instagram</span>
	   </a>
	{% endif %}
	{% if item.youtube %}
	    <a style="padding-left:10px;" href="https://www.youtube.com/channel/{{ item.youtube }}" title="YouTube">
	     	<i class="fab fa-youtube"></i>
	      <span class="sr-only">YouTube</span>
	   </a>
	{% endif %}
	</p>
    {% endfor %}
{% endfor %}
</div>

<h2 class="title is-3 horizontal-line">Achievements in 2023</h2>
The Pickaway County Democratic Party is pleased to share the following report of achievements with the people of Pickaway County. 

 * Fielded 3 local candidates for office
 * Awarded 4-$300 Engage for the Future Scholarships to deserving senior-year students in the county
 * Collected signatures to get Reproductive Rights on the ballot
 * Enter the Contest Every Race Grant Program
 * Won the August special election on Repro Rights and against suppression of democracy
 * Held a young Dems event
 * Hosted a successful Pumpkin Show booth
 * Entered a float for the Pickaway County Democratic Party in the Friday parade
 * Partnered with the Second Baptist Church to hold a Race-Class Narrative training that was a big success
 * Partnered with the Presbyterian Church and PICCA and Ohio House Shelter to hold a Veterans Day Donation Drive that generated massive amounts of needed/requested items and $2,500+ in financial donations
 * Partnered with Haven House for the second annual Haven House Holiday celebration generating donations for residents of a huge amount of needed materials and $2,000+ in cash and gift card donations

We are eagerly looking forward to 2024 being an even more successful year for the Pickaway County Democratic Party and hope you will join us as we move into this critically important campaign year. Thank you for your support!  In solidarity!



