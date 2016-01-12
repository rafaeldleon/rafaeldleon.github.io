---
layout: master
title: Rafael S. Gonz&aacute;lez D'le&oacute;n's Web Page
---

<h2>Research Interests</h2>

<em>Algebraic and Topological Combinatorics.</em>

<h2>Upcoming events and activities</h2>

<p>June 13-24, 2016. 5th Encuentro Colombiano de Combinatoria ECCO 2016. Universidad de Antioquia. Medellin, Colombia.</p>
<p>July 4-8, 2016. FPSAC 2016. Vancouver, British Columbia, Canada .</p>
<p>July 11-15, 2016. V Congreso Latinoamericano de Matematicos. Universidad del Norte. Barranquilla, Colombia.</p>
<p>November 7-11, 2016. Workshop "Polyhedral geometry and partition theory". American Institute of Mathematics, San Jose, CA, USA.</p>


<h2>Preprints and Publications</h2>

<ol>
{% for article in site.publications%}
<li><table width="95%"><tr> {{article.authors}}. <strong>{{article.title}}</strong>.<br/>
<a href="{{article.location_url}}">{{article.location_name}}.</a> 
<a name="{{article.title}}" href="{{ root_url }}{{ article.url }}" class="showinfo"> See abstract.</a><br/>
</tr></table></li><br/>
{% endfor %}
</ol>