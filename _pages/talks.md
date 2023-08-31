---
layout: page
permalink: /talks/
title: talks & posters
nav: true
nav_order: 4
---
<!-- _pages/talks.md -->


<div class="publications">

<h3>Talks</h3>

 
<ol reversed="">
{% for talk in site.data.talks %}
    <li>
    <strong>{{ talk.text }}</strong> <br /> 
    {{ talk.location }}, {{ talk.date }}, {{ talk.type }} <br />
    {% if talk.link %}
    <a href="{{ talk.link }}" target="_blank">{{ talk.title }}</a>
    {% else %}
      <i>{{ talk.title }}</i>
    {%- endif %}
    </li>  
{% endfor %}
</ol>


<h3>Posters</h3>

<ol reversed="">
{% for poster in site.data.posters %}
    <li>
    <strong>{{ poster.text }}</strong> <br /> 
    {{ poster.location }}, {{ poster.date }} <br />
    <a href="/assets/posters/{{ poster.file }}" target="_blank">{{ poster.title }}</a>
    </li>  
{% endfor %}
</ol>


</div>
