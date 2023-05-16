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
<a href="https://votenoinaugust.org/">
	<figure class="image is-3by2">
		<img src="/img/No-In-August-v1.png">
	</figure>
</a>
## We are the Pickaway County Democratic party.
### Our mission is to work together to elect democracy-supporting, civic-minded individuals to local, state, and national offices.
<h2 class="title is-3 horizontal-line">
Reproductive Freedom Petition
</h2>

Haven't signed the petition for the Right To Reproductive Freedom yet? **Let us come to you!**  
We want to give every resident of Pickaway County the opportunity to sign, even if they can't come to one of our events.  
Fill out the form below and one of our petition circulators will contact you to find the time that works best for you.  
You can read the full text of the petition <a href="https://www.ohioattorneygeneral.gov/getattachment/cf27c10f-b153-4731-ae9e-e3555a326ed9/The-Right-to-Reproductive-Freedom-with-Protections-for-Health-and-Safety.aspx">here</a>.
<div class="box">
<form
  method="POST" 
  action="https://script.google.com/macros/s/AKfycbxI2OgrWswwyaHp4lXVguvWHGQeHm8PoJPbt0FpJSdgDq60mesVjEcA4vo8KQoTHHhLqg/exec"
  autocomplete="on"
  id="petition-form"
>
<div class="field">
  <label class="label">Name</label>
  <div class="control">
    <input autocomplete="name" name="Name" class="input" type="text" required>
  </div>
</div>

<div class="field">
  <label class="label">Home Address</label>
  <div class="control">
    <input autocomplete="street-address" name="Address" class="input" type="text" required>
  </div>
</div>

<div class="field">
  <label class="label">City</label>
  <div class="control">
    <input autocomplete="city" name="City" class="input" type="text" required>
  </div>
</div>

<div class="field">
  <label class="label">Email</label>
  <div class="control">
    <input autocomplete="email" name="Email" class="input" type="email" required>
  </div>
</div>

<div class="field">
  <label class="label">Phone</label>
  <div class="control">
    <input autocomplete="tel" name="Phone" class="input" type="tel" required>
  </div>
</div>

<div class="field">
  <label class="label">Message</label>
  <div class="control">
    <textarea name="Message" class="textarea" placeholder="Optional Message"></textarea>
  </div>
</div>
If you don't check the boxes below, we'll bring extra forms to register you and/or update your voter registration.<br><br>
<div class="field">
  <div class="control">
    <label class="checkbox">
      <input type="checkbox" name="Registered">
      I'm registered to vote in Pickaway County <a href="https://lookup.boe.ohio.gov/vtrapp/pickaway/vtrlookup.aspx#">(check here)</a>
    </label>
  </div>
</div>
<div class="field">
  <div class="control">
    <label class="checkbox">
      <input type="checkbox" name="RegUpdate">
      My voter registration is up to date
    </label>
  </div>
</div>
<div class="field is-grouped">
  <div class="control">
    <button type="submit" class="button is-link">Submit</button>
  </div>
</div>
</form>
</div>

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
