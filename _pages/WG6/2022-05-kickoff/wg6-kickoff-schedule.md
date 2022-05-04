---
title: "WG6 kick-off meeting: Syntax and Semantics of Type Theories — Schedule"
layout: single
permalink: /wg6-kickoff-stockholm/schedule.html
---

## Overview

{% for item in site.wg6-kickoff %}
  {% capture day %}{{ item.date | date: '%Y%m%d' }}{% endcapture %}
  {% capture prevday %}{{ item.previous.date | date: '%Y%m%d' }}{% endcapture %}
  {% capture nextday %}{{ item.next.date | date: '%Y%m%d' }}{% endcapture %}

  {% if day != prevday %}
  <h4 class="date" id="{{ day }}">{{ item.date | date: "%A %e %B" }}</h4>
  {% endif %}

  {% capture starttime %}{{ item.date | date: '%-H.%M' }}{% endcapture %}
  {% if item.endtime != nil %}
    {% capture timerange %}{{ starttime }}–{{ item.endtime | date: '%-H.%M' }}{% endcapture %}
  {% elsif day == nextday %}
    {% capture timerange %}{{ starttime }}–{{ item.next.date | date: '%-H.%M' }}{% endcapture %}
  {% else %}
    {% capture timerange %}{{ starttime }}{% endcapture %}
  {% endif %}

  {% capture speakername %}{{ item.speakerfirst }} {{ item.speakermiddle }} {{ item.speakerlast }}{% endcapture %}

<div class="talk">
  <div class="talktitle"><p>
    {{ timerange }}:
    {% if item.istalk %}
      <strong>{{ speakername }}</strong>, <a href="#{{ speakername | slugify: "latin" }}-abstract"><em>{{ item.title }}</em></a>
    {% else %}
      <em>{{ item.description | markdownify | remove: '<p>' | remove: '</p>' }}</em>
    {% endif %}
  </p></div>

</div>
{% endfor %}


### Social activities

Details TBA.

### Abstracts

{% for talk in site.wg6-kickoff %}  <!-- TODO: filter by istalk at this point -->
  {% capture day %}{{ talk.date | date: '%Y%m%d' }}{% endcapture %}
  {% capture prevday %}{{ talk.previous.date | date: '%Y%m%d' }}{% endcapture %}
  {% capture nextday %}{{ talk.next.date | date: '%Y%m%d' }}{% endcapture %}

  {% if day != prevday %}
  <h4 class="date">{{ talk.date | date: "%A %e %B" }}</h4>
  {% endif %}

  {% if talk.istalk %}

  {% capture starttime %}{{ talk.date | date: '%-H.%M' }}{% endcapture %}
  {% if talk.endtime != nil %}
    {% capture timerange %}{{ starttime }}–{{ talk.endtime | date: '%-H.%M' }}{% endcapture %}
  {% elsif day == nextday %}
    {% capture timerange %}{{ starttime }}–{{ talk.next.date | date: '%-H.%M' }}{% endcapture %}
  {% else %}
    {% capture timerange %}{{ starttime }}{% endcapture %}
  {% endif %}

  {% capture speakername %}{{ talk.speakerfirst }} {{ talk.speakermiddle }} {{ talk.speakerlast }}{% endcapture %}

  {% if talk.speakeraffiliation != nil %}
    {% capture speakeraffiliation %} ({{ talk.speakeraffiliation }}){% endcapture %}
  {% else %}
    {% capture speakeraffiliation %}{% endcapture %}
  {% endif %}

  <div class="talk">
  <div class="talktitle" id="{{ speakername | slugify: "latin" }}-abstract"><p>
    {{ timerange }}:
    <strong>{{ speakername }}</strong>{{ speakeraffiliation }}, <em>{{ talk.title }}</em>
  </p></div>

    <div class="abstract">
      {{ talk.content }}
    </div>

	{% if talk.slides != nil %}
	<div class="slides">
	  <p><strong><a href="slides/{{ talk.slides }}">Slides</a></strong></p>
    </div>
	{% endif %}
  </div>
  {% endif %}
{% endfor %}