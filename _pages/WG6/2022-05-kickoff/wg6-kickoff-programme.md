---
title: "WG6 kick-off meeting: Syntax and Semantics of Type Theories — Programme"
layout: single
permalink: /wg6-kickoff-stockholm/programme.html
---

[Overview](#overview) — [Social activities](#social-activities) — [Abstracts](#abstracts) — [Meeting homepage](/wg6-kickoff-stockholm)

{% assign schedule-items = site.wg6-kickoff | where:"exclude", false  %}
{% assign talks = schedule-items | where:"istalk", true  %}

## Overview

<p>
All talks will take place in room 14, house 5, at Kräftriket ([map](https://w3w.co/wink.breathy.crystals)).
</p>

<ul>
{% for item in schedule-items %}
  {% capture day %}{{ item.date | date: '%Y%m%d' }}{% endcapture %}
  {% capture prevday %}{{ item.previous.date | date: '%Y%m%d' }}{% endcapture %}
  {% capture nextday %}{{ item.next.date | date: '%Y%m%d' }}{% endcapture %}

  {% if day != prevday %}
  </ul>
  <h4 class="date" id="{{ day }}">{{ item.date | date: "%A %e %B" }}</h4>
  <ul>
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


<!-- item.url {{ item.url }}; item.previous.url {{item.previous.url }} ; prevday {{ prevday }} -->
<li><span class="talk" id="{{ item.url }}">
    {{ timerange }}:
    {% if item.istalk %}
      <strong>{{ speakername }}</strong>, <a href="#{{ speakername | slugify: "latin" }}-abstract"><em>{{ item.title }}</em></a>
    {% else %}
      <em>{{ item.description | markdownify | remove: '<p>' | remove: '</p>' }}</em>
    {% endif %}
</span></li>

{% endfor %}
</ul>

### Social activities

Details TBA.

### Abstracts

{% for talk in talks %}
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
	  <p><strong><a href="/assets/documents/wg6-kickoff-slides/{{ talk.slides }}">Slides</a></strong></p>
    </div>
	{% endif %}
  </div>
  {% endif %}
{% endfor %}
