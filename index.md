---
title: Home
description: Official website for the Pickaway County Democratic Party - Ohio
hide_hero: true
hero_height: 0
layout: page
callouts: home_callouts
show_sidebar: true
show_latest_posts: true
show_candidates: false
---
<script>
window.addEventListener("load", function() {
  const form = document.getElementById('petition-form');
  form.addEventListener("submit", function(e) {
    e.preventDefault();
    const data = new FormData(form);
    const action = e.target.action;
    fetch(action, {
      method: 'POST',
      body: data,
    })
    .then(() => {
      alert("Form Submitted, thank you!");
    })
  });
});
</script>
<style>
.horizontal-line {
    padding-top: 20px;
    border-top: 5px solid #1884B3; 
}
</style>
## We are the Pickaway County Democratic party.
### Our mission is to work together to elect democracy-supporting, civic-minded individuals to local, state, and national offices.

<a href="https://votenoinaugust.org/">
	<figure class="image is-3by2">
		<img src="/img/OPOV 2 Color -Logo1.png">
	</figure>
</a>

### **There will be a special meeting of Central/Executive committee members representing precincts within the city of Circleville.**
The meeting will be held at 6:15pm, July 6, 2023, at the Pickaway County Library. This will be in the Crites-Hannan meeting room immediately preceding the monthly executive committee meeting. 

The purpose of this meeting is to consider nomination of candidates for the open slot on the mayoral ballot for the November election.




<h2 class="title is-3 horizontal-line">
Special Election: August 8th
</h2>
<p class="is-size-5">
July 10: Voter Registration Deadline<br>
July 11: Early Voting Begins<br>
August 1: Absentee Ballot Request Deadline<br>
</p>

<h2 class="title is-3 horizontal-line">
General Election: November 7th
</h2>
<p class="is-size-5">
October 10: Voter Registration Deadline<br>
October 11: Early Voting Begins<br>
October 31: Absentee Ballot Request Deadline<br>
</p>

