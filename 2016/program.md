---
layout: 2016/page
title: Compose Conference 2016 Program
permalink: /2016/program/
---

Register at <a href="http://composeconference.eventbrite.com">composeconference.eventbrite.com</a>

---

<!-- Thursday's schedule -->
## Thursday, February 4, 2016

<table class="table table-bordered" style="background: #fff">
    <tr class="active"><th width="200">Time</th><th>Talk</th></tr>
    <tr><td>8:30am - 9:00am</td><td>Registration</td></tr>
    <tr><td>9:00am - 9:15am</td><td>Opening<br/></td></tr>
    <tr><td>9:15am - 10:15am</td><td>Keynote: How to Bake 'How to Bake Pi': reflections on making abstract mathematics palatable<br/>Dr. Eugenia Cheng<br/></td></tr>
    <tr><td>10:15am - 10:30am</td><td>Break<br/></td></tr>

{% assign sorted = (site.data.2016.speakers.speakers | sort: 'start_time') %}

{% for speaker in sorted %}

  {% if speaker.start_time <= '2016-02-04 11:50:00 -0500' %}
    <tr>
      <td>{{ speaker.start_time | date: '%H:%M%P' }} - {{ speaker.end_time | date: '%H:%M%P' }}</td>
      <td>        
        <p class="lead">
          <b>{{ speaker.title }}</b> <br/>
            <small>
                {{ speaker.name }}
            </small>
        </p> 
        <blockquote class="abstract">
            {{ speaker.abstract | markdownify }}
        </blockquote>
      </td>
    </tr>
  {% endif %}
{% endfor %}                
<tr><td>11:50am - 12:50pm</td><td>Lunch<br/></td></tr>

{% for speaker in sorted %}
  {% if speaker.start_time >= '2016-02-04 12:50:00 -0500' %}
  {% if speaker.start_time <= '2016-02-04 15:10:00 -0500' %}
    <tr>
      <td>{{ speaker.start_time | date: '%H:%M%P' }} - {{ speaker.end_time | date: '%H:%M%P' }}</td>
      <td>        
        <p class="lead">
          <b>{{ speaker.title }}</b> <br/>
            <small>
                {{ speaker.name }}
            </small>
        </p> 
        <blockquote class="abstract">
            {{ speaker.abstract | markdownify }}
        </blockquote>
      </td>
    </tr>
  {% endif %}
  {% endif %}
{% endfor %}   

<tr><td>3:10pm - 3:30pm</td><td>Break<br/></td></tr>

{% for speaker in sorted %}
  {% if speaker.start_time >= '2016-02-04 15:30:00 -0500' %}
  {% if speaker.start_time <= '2016-02-04 18:00:00 -0500' %}
    <tr>
      <td>{{ speaker.start_time | date: '%H:%M%P' }} - {{ speaker.end_time | date: '%H:%M%P' }}</td>
      <td>        
        <p class="lead">
          <b>{{ speaker.title }}</b> <br/>
            <small>
                {{ speaker.name }}
            </small>
        </p> 
        <blockquote class="abstract">
            {{ speaker.abstract | markdownify }}
        </blockquote>
      </td>
    </tr>
  {% endif %}
  {% endif %}
{% endfor %}   
             
</table>

---

<!-- Friday's schedule -->
## Friday, February 5, 2016
<table class="table table-bordered" style="background: #fff">
    <tr class="active"><th width="200">Time</th><th>Talk</th></tr>
    <tr><td>8:30am - 9:00am</td><td>Registration</td></tr>

{% for speaker in sorted %}
  {% if speaker.start_time >= '2016-02-05 00:00:00 -0500' %}
  {% if speaker.start_time <= '2016-02-05 11:30:00 -0500' %}
    <tr>
      <td>{{ speaker.start_time | date: '%H:%M%P' }} - {{ speaker.end_time | date: '%H:%M%P' }}</td>
      <td>        
        <p class="lead">
          <b>{{ speaker.title }}</b> <br/>
            <small>
                {{ speaker.name }}
            </small>
        </p> 
        <blockquote class="abstract">
            {{ speaker.abstract | markdownify }}
        </blockquote>
      </td>
    </tr>
  {% endif %}
  {% endif %}
{% endfor %}                
<tr><td>11:30am - 12:30pm</td><td>Lunch<br/></td></tr>

{% for speaker in sorted %}
  {% if speaker.start_time >= '2016-02-05 00:00:00 -0500' %}
  {% if speaker.start_time <= '2016-02-05 11:30:00 -0500' %}
    <tr>
      <td>{{ speaker.start_time | date: '%H:%M%P' }} - {{ speaker.end_time | date: '%H:%M%P' }}</td>
      <td>        
        <p class="lead">
          <b>{{ speaker.title }}</b> <br/>
            <small>
                {{ speaker.name }}
            </small>
        </p> 
        <blockquote class="abstract">
            {{ speaker.abstract | markdownify }}
        </blockquote>
      </td>
    </tr>
  {% endif %}
  {% endif %}
{% endfor %}                
<tr><td>3:00pm - 3:10pm</td><td>Break<br/></td></tr>
{% for speaker in sorted %}
  {% if speaker.start_time >= '2016-02-05 15:10:00 -0500' %}
  {% if speaker.start_time <= '2016-02-05 18:00:00 -0500' %}
    <tr>
      <td>{{ speaker.start_time | date: '%H:%M%P' }} - {{ speaker.end_time | date: '%H:%M%P' }}</td>
      <td>        
        <p class="lead">
          <b>{{ speaker.title }}</b> <br/>
            <small>
                {{ speaker.name }}
            </small>
        </p> 
        <blockquote class="abstract">
            {{ speaker.abstract | markdownify }}
        </blockquote>
      </td>
    </tr>
  {% endif %}
  {% endif %}
{% endfor %} 

<tr><td>5:40-5:50pm</td><td>Closing</td></tr>
</table>
