---
layout: master
title: Rafael S. Gonz&aacute;lez D'le&oacute;n's Web Page
---

<h2>Research Interests</h2>

<em>Algebraic and Topological Combinatorics.</em>

<h2>Upcoming events and activities</h2>

<p>September 25, 2017 Applied Algebra seminar. York University, Toronto, ON, CA. </p>
<p>October 16, 2017 Discrete CATS seminar. University of kentucky, Lexington, KY, US. </p>
<p>June 4-15, 2018 Encuentro Colombiano de Combinatoria ECCO 2018 
<a href="http://ecco2018.combinatoria.co/">http://ecco2018.combinatoria.co/</a>. 
Universidad del Norte, Barranquilla, Colombia. </p>
<p>July 26-29, 2018 ICM Satellite Conference: A Pan-Hemispheric Celebration of
Mathematics in Miami. University of Miami, Coral Gables, FL, US. </p>



<h2>Preprints and Publications</h2>

<ol>
{% for article in site.publications%}
<li><table width="95%"><tr> {{article.authors}}. <strong>{{article.title}}</strong>.<br/>
<a href="{{article.location_url}}">{{article.location_name}}.</a> 
<a name="{{article.title}}" href="{{ root_url }}{{ article.url }}" class="showinfo"> See abstract.</a><br/>
</tr></table></li><br/>
{% endfor %}
</ol>
