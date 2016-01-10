---
layout: 2016/page
title: Unconference & Exchange Workshops
permalink: /2016/workshops/
---

Coming Soon

{% for workshop in site.data.2016.unconference.workshops %}

<hr>

<div id="workshop">
<div class="container">
<div class="row">
    <div class="col-lg-8 col-md-8 col-sm-8 col-xs-8">
      <h2>{{ workshop.presenter }}</h2>
      <h3>{{ workshop.title }}</h3>
      <p>
        {{ workshop.abstract | markdownify }}
  </p>
</div>
<div class="col-lg-4 col-md-4 col-sm-4 col-xs-4">
<h2>&nbsp;</h2>
<h3>&nbsp;</h3>
<p class="text-centered">
{% if workshop.speaker.twitter %}
<a href="http://twitter.com/{{ workshop.speaker.twitter }}">
 <i class="fa fa-twitter"> {{ workshop.speaker.twitter }}</i>
</a>
{% endif %}
{% if workshop.speaker.github %}
<a href="http://github.com/{{ workshop.speaker.github }}">
 <i class="fa fa-github"> {{ workshop.speaker.github }}</i>
</a>
{% endif %}
{% if workshop.speaker.irc_handle %}
IRC: {{ workshop.speaker.irc_handle }}</i>
{% endif %}
</p>
</div>
</div><!-- --/row ---->
</div><!-- --/container ---->
</div>
{% endfor %}