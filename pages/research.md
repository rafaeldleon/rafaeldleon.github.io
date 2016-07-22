---
layout: master
title: Rafael S. Gonz&aacute;lez D'le&oacute;n's Web Page
---

<h2>Research Interests</h2>

<em>Algebraic and Topological Combinatorics.</em>

<h2>Upcoming events and activities</h2>


<p>September 24-25, 2016 AMS Special Session on Plethysm and Kronecker Products, Brunswick, ME, USA.</p>
<p>November 7-11, 2016. Workshop "Polyhedral geometry and partition theory". American Institute of Mathematics, San Jose, CA, USA.</p>
<p>January 4-7, 2017. AMS Special Session on Applications of Partially Ordered Sets in Algebraic, 
Topological, and Enumerative Combinatorics at the 2017 Joint Mathematics Meetings, Atlanta, GA, USA</p>
<p>April 1-2, 2017 AMS Special Session on Algebraic and Enumerative Combinatorics with Applications, Bloomington, IN, USA.</p>

<h2>Preprints and Publications</h2>

<ol>
{% for article in site.publications%}
<li><table width="95%"><tr> {{article.authors}}. <strong>{{article.title}}</strong>.<br/>
<a href="{{article.location_url}}">{{article.location_name}}.</a> 
<a name="{{article.title}}" href="{{ root_url }}{{ article.url }}" class="showinfo"> See abstract.</a><br/>
</tr></table></li><br/>
{% endfor %}
</ol>
