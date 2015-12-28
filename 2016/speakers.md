---
layout: page2016
title: Compose Conference 2016 Speakers
permalink: /2016/speakers/
---

Register at <a href="http://composeconference.eventbrite.com">composeconference.eventbrite.com</a>

---

<div id="biowrap">
	<div class="container">
	<div class="row">
	    <div class="col-lg-8 col-md-8 col-sm-8 col-xs-8">
		<h2>Eugenia Cheng</h2>
		<h3><small>[KEYNOTE]</small> How to Bake 'How to Bake Pi': reflections on making abstract mathematics palatable</h3>
		<p>
		</p>
	    </div>
	</div><!-- --/row ---->
	</div><!-- --/container ---->
</div>


{% for speaker in site.data.2016.speakers.speakers %}

<hr>

<div id="biowrap">
    <div class="container">
	<div class="row">
	    <div class="col-lg-8 col-md-8 col-sm-8 col-xs-8">
		<h2>{{ speaker.name }}</h2>
		<h3>{{ speaker.title }}</h3>
		<p>
		  {{ speaker.abstract }}
		</p>
	    </div>
	</div><!-- --/row ---->
    </div><!-- --/container ---->
</div>
{% endfor %}

---

Register at <a href="http://composeconference.eventbrite.com">composeconference.eventbrite.com</a>
