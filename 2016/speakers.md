---
layout: 2016/page
title: Compose Conference 2016 Speakers
permalink: /2016/speakers/
---

Register for C◦mp◦se :: Conference 2016 tickets at [composeconference.eventbrite.com](http://composeconference.eventbrite.com)

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
      <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4">
      <h2>&nbsp;</h2>
      <h3><small>{{ speaker.start_time | date: '%h %-d, %I:%M%P'}}</small></h3>
      <p class="text-centered">
{% if speaker.twitter %}
<a href="http://twitter.com/{{ speaker.twitter }}">
 <i class="fa fa-twitter"> {{ speaker.twitter }}</i>
</a>
{% endif %}
{% if speaker.github %}
<a href="http://github.com/{{ speaker.github }}">
 <i class="fa fa-github"> {{ speaker.github }}</i>
</a>
{% endif %}
{% if speaker.irc_handle %}
IRC: {{ speaker.irc_handle }}</i>
{% endif %}
</p>
</div>
</div><!-- --/row ---->
</div><!-- --/container ---->
</div>
{% endfor %}

---

Register for C◦mp◦se :: Conference 2016 tickets at [composeconference.eventbrite.com](http://composeconference.eventbrite.com)
