---
layout: page2016
title: Travel Information
permalink: /2016/travel/
---

Here are some hotels in walking distance to the conference venue.

<div id="hotels">
	<div class="container">
		<div class="row">
{% for hotel in site.data.2016.hotels.hotels %}
			<div class="col-lg-4 col-md-4 col-sm-4 col-xs-4">
			<h3>{{ hotel.name }}</h3>
			<h4>{{ hotel.address }}</h4>
			<p style="min-height:60px;"> 
				<a href="{{ hotel.url }}">Link</a>
			{{ hotel.desc }}
			</p>
			</div>
{% endfor %}
		</div><! --/row --> 
	</div><! --/container -->
</div>

<hr style="border:1px dotted #efefee "/>
