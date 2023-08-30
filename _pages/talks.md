---
layout: page
permalink: /talks/
title: talks & posters
nav: true
nav_order: 3
---
<!-- _pages/talks.md -->


<div class="publications">

<h3>Talks</h3>

 
<ol reversed="">
{% for talk in site.data.talks %}
    <li><strong>{{ talk.title }}</strong><br />
      {{ talk.type }}; {{ talk.text }}; {{ talk.location }}, {{ talk.date }} 
      </li>  
{% endfor %}
</ol>


<h3>Posters</h3>

  <ol>
    <li><strong><a href="https://www.astro.rug.nl/~rab/data/uploads/poster.pdf" target="_blank">The chemistry of episodic accretion</a></strong><br />
      <a href="http://www.astrochemistry.org.uk/IAU_S350/">IAUS 350: Laboratory Astrophysics: from Observations to Interpretation</a>, Cambridge, Apr. 2019</li>
    <li><strong><a href="https://www.astro.rug.nl/~rab/data/uploads/posterrostock.pdf">The planet-forming disk HD 163296 Gas gaps ... or not?</a></strong><br />
      <a href="http://pfe2019.stat.physik.uni-rostock.de/">Planet Formation and Evolution</a>, Rostock, Feb. 2019</li>
    <li><strong><a href="https://www.astro.rug.nl/~rab/data/uploads/postervienna.pdf" target="_blank">Constraining the stellar energetic particle flux in young solar-like stars</a></strong><br />
      <a href="https://astronomy2018.univie.ac.at/symposia/symposium345/" target="_blank">IAU GA Symposium "Origins: From the Protosunto the First Steps of Life"</a>, Vienna Aug. 2018</li>
  </ol>

</div>
