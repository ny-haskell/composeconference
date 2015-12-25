---
layout: page2016
title: Compose Conference 2016
permalink: /2016/speakers/
---

<div id="biowrap">
	<div class="container">
	<div class="row">
	    <div class="col-lg-8 col-md-8 col-sm-8 col-xs-8 col-lg-offset-3 col-md-offset-3 col-sm-offset-3 col-xs-offset-3">
		<h2>Eugenia Cheng</h2>
		<h3><small>[TECHNICAL KEYNOTE]</small> How to Bake 'How to Bake Pi': reflections on making abstract mathematics palatable</h3>
		<p>
		</p>
	    </div>
	</div><!-- --/row ---->
	</div><!-- --/container ---->
</div>

{% for speaker in site.data.2016.speakers.speakers %}
<div id="biowrap">
    <div class="container">
	<div class="row">
	    <div class="col-lg-3 col-md-3 col-sm-3 col-xs-3">
		<img src="" class="img-responsive">
	    </div>
	    <div class="col-lg-8 col-md-8 col-sm-8 col-xs-8">
		<h2>{{ speaker.name }}</h2>
		<h3>{{ speaker.title }}</h3>
		<p>
		</p>
	    </div>
	</div><!-- --/row ---->
    </div><!-- --/container ---->
</div>
{% endfor %}
