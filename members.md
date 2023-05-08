---
title: Central & Exectutive Committee Members
description: List of members for the central and executive committees for the Pickaway County Democratic Party
hide_hero: false
hero_height: is_small
layout: page
callouts: 
show_sidebar: false
show_latest_posts: false
---
<style>
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto;
}
.columns {
  gap: 3rem;
}
</style>
<h1>Pickaway County Democratic Party<br>Central & Executive Committees</h1>
<p style="font-size:16px">The Pickaway County Democratic Party is governed by the Central Committee which in turn confers all power and authority upon the Executive Committee pursuant to the party's constitution and by-laws.<br><br>

Every two years (in even-numbered years) during the primary election, each of the 43 voting precincts in the county elect one person to represent their respective precinct on the central committee.  Following the election, the Central Committee members meet, organize and elect officers to lead the party for the next two years.</p>

<h2>Leadership</h2>
<p style="font-size:20px">Chairperson - {{ site.data.members.chair }}<br>
Vice-Chair - {{ site.data.members.vc }}<br>
Secretary - {{ site.data.members.secretary }}<br>
Treasurer - {{ site.data.members.treasurer }}<br>
</p>

<h2>Central & Executive Committee</h2>
<div class="columns is-multiline">
{% for item in site.data.members.central %}
  {% if item.name %}
    <div class="is-one-quarter">
    <p style="font-size:20px">{{ item.name }}</p>
    {{ item.precinct }}
    </div>
  {% endif %}
{% endfor %}
</div>


<h2>Executive Committee at-Large</h2>
<div class="grid-container">
{% for item in site.data.members.atlarge %}
  {% if item.name %}
    <div class="block">
    <p style="font-size:20px">{{ item.name }}</p>
    </div>
  {% endif %}
{% endfor %}
</div>
