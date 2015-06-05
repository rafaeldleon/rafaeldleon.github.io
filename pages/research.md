---
layout: master
title: Rafael S. Gonz&aacute;lez D'le&oacute;n's Web Page
---

<h2>Research Interests</h2>

<em>Algebraic and Topological Combinatorics.</em>

<h2>Upcoming events and activities</h2>

<p>August 26-30, 2015. Algebraic Combinatorics and Applications, The first annual Kliakhandler Conference.
Michigan Technological University, Houghton, MI, USA</p>

<p>October 3-4, 2015. Special Session on Enumerative Algebraic and
geometric combinatorics. AMS Sectional Meeting. Loyola University. Chicago, IL, USA.</p>

<p>October 17-18, 2015. Special Session on Topological Combinatorics. AMS Sectional Meeting. University of Memphis. Memphis, TN, USA.</p>

<h2>Preprints and Publications</h2>

<ol>
{% for article in site.publications%}
<li><table width="95%"><tr> {{article.authors}}. <strong>{{article.title}}</strong>.<br/>
<a href="{{article.location_url}}">{{article.location_name}}.</a> 
<a name="{{article.title}}" href="{{ root_url }}{{ article.url }}" class="showinfo"> See abstract.</a><br/>
</tr></table></li><br/>
{% endfor %}
</ol>