---
layout: page
navigation_title: Contributors
title: Contributors
permalink: /contributors/
---

Here are the list of amazing Mozilla contributors from our club.


<div class="contributors">
<h3>Present Contributors</h3>
{% for contributor in site.data.present_contributors %}

	<div id="pic" style="height: 130px; width: 130px"><img src="{{ contributor.photo }}"></div>
	<p class="name">Name: {{ contributor.name }}</p>
	<p class="contribution">Primary Area of Contribution: {{ contributor.contribution }}</p>
	

{% endfor %}
<div>

<h3>Past Contributors</h3>

<div class="contributors">
{% for contributor in site.data.past_contributors %}

	<div class="pic" style="height: 130px; width: 130px"><img src="{{ contributor.photo }}"></div>
	<p class="name">Name: {{ contributor.name }}</p>
	<p class="contribution">Primary Area of Contribution:{{ contributor.contribution }}</p>

{% endfor %}
</div>

