---
layout: 2016/page
title: C◦mp◦se 2016 Summary
permalink: /2016/summary/
---

  <div id="biowrap">
  <div class="container">
  <div class="row">
      <div class="col-lg-8 col-md-8 col-sm-8 col-xs-8">
        <h2>Eugenia Cheng</h2>
        <h3>How to Bake 'How to Bake Pi': Reflections on Making Abstract Math Palatable</h3>
        <p>
           
        </p>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4">
      <h2>&nbsp;</h2>
      <h3><small>Feb 4, 9:15am</small></h3>
      <p class="text-centered">

<a href="http://twitter.com/DrEugeniaCheng">
 <i class="fa fa-twitter"> DrEugeniaCheng</i>
</a>
<br/>
<img class="img-responsive" src="http://img.youtube.com/vi/h2p68JjSUH0/hqdefault.jpg" alt="{{speaker.title}} by Eugenia Cheng">
<br/>
<i class="fa fa-youtube"></i> <a href="http://youtube.com/watch?v=h2p68JjSUH0">How to Bake 'How to Bake Pi': Reflections on Making Abstract Math Palatable</a>
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
      <br/>
{% if speaker.twitter %}
<a href="http://twitter.com/{{ speaker.twitter }}"><i class="fa fa-twitter"> </i> {{ speaker.twitter }}</a>
{% endif %}
{% if speaker.github %}
<a href="http://github.com/{{ speaker.github }}"><i class="fa fa-github"> </i> {{ speaker.github }}</a>
{% endif %}
{% if speaker.irc_handle %}
IRC: {{ speaker.irc_handle }}</i>
{% endif %}

{% if speaker.youtubeId %}
<br/>
<img class="img-responsive" src="http://img.youtube.com/vi/{{speaker.youtubeId}}/hqdefault.jpg" alt="{{speaker.title}} by {{speaker.name}}">
<br/>
<i class="fa fa-youtube"></i> <a href="http://youtube.com/watch?v={{speaker.youtubeId}}">{{speaker.title}}</a>
{% endif %}
</p>
</div>
</div><!-- --/row ---->
</div><!-- --/container ---->
</div>
{% endfor %}
