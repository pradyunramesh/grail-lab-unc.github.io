---
title: "GRAIL Lab - Team"
layout: gridlay
excerpt: "GRAIL Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 <!-- **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!** -->

## Principal Investigator

{% assign pis = site.data.people | where: "title", "pi"  %}
{% include people.html people = pis %}

<div class='row'></div>


{% assign phds = site.data.people | where: "title", "phd"  %}
{% if phds.size > 0 %}
  <h2> PhD Students </h2>
  {% include people.html people = phds %}
  <div class='row'></div>
{% endif %}

{% assign masters = site.data.people | where: "title", "masters"  %}
{% assign bachelors = site.data.people | where: "title", "bachelors"  %}
{% if masters.size > 0 %}
  <h2 Masters and Bachelors Students </h2>
  {% include people.html people = masters %}
  {% include people.html people = bachelors %}
  <div class='row'></div>
{% endif %}


## Alumni

{% assign number_printed = 0 %}
<ul>
{% for member in site.data.alumni %}
<li>
  {% if member.link != "" and member.link != nil %}
    <a href="{{ member.link }}">{{ member.name }}</a> ({{ member.info }}), {{ member.duration.start }} - {{ member.duration.end }}
  {% else %}
    {{ member.name }}({{ member.info }}), {{ member.duration.start }} - {{ member.duration.end }}
  {% endif %}
</li>
{% endfor %}
</ul>
