---
layout: 2016/page
title: Travel & Accomodation Information
permalink: /2016/travel/
---


##Transportation

<div class="row">
	<div class="col-lg-4 col-md-4 col-sm-4 proc">
		<h3><i class="fa fa-flag-o"></i> Subway</h3>
		<p>The subway runs at all hours and goes just about everywhere. The nearest stop is the 2/3 and R train station at Jay St/MetroTech.</p>
	</div>
	<div class="col-lg-4 col-md-4 col-sm-4 proc">
		<h3><i class="fa fa-flag-o"></i> Train</h3>
		<p>Take Amtrak to Penn Station, which is located in Midtown Manhattan, or the Metro-North to Grand Central.</p>
	</div>
	<div class="col-lg-4 col-md-4 col-sm-4 proc">
		<h3><i class="fa fa-plane"></i> Airports</h3>
		<p>The closest major airports are John F. Kennedy International Airport (JFK), LaGuardia Airport (LGA), and Newark International Airport (EWR). All are accessible by public transportation - train, bus, shuttles.</p>
	</div>
</div>

<hr>

## Hotels

NYC has many fine hotels and hostels. We suggest something by the 2/3, R, 4/5, A/C, or G lines.  Here are some hotels in walking distance to the conference venue.

<div id="hotels">
	<div class="container">
		<div class="row">
{% for hotel in site.data.2016.hotels.hotels %}
			<div class="col-lg-4 col-md-4 col-sm-4 col-xs-4">
			<h3>
				<i class="fa fa-building-o"></i> 
				<a href="{{ hotel.url }}">{{ hotel.name }}</a>
			</h3>
			<h4>{{ hotel.address }}</h4>
			<p style="min-height:60px;"> 
			{{ hotel.desc }}
			</p>
			</div>
{% endfor %}
		</div><! --/row --> 
	</div><! --/container -->
</div>

<hr style="border:1px dotted #efefee "/>
