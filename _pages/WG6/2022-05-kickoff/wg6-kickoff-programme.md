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
All talks will take place in room 14, house 5, at Kräftriket (<a href="https://w3w.co/wink.breathy.crystals">map</a>).
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

The workshop dinner is 19:00 at [Shahrzad](http://shahrzad.se), a classic Persian restaurant, [30mins walk](https://goo.gl/maps/gCcAvdpsReJ2Ut6z90) from Kräftriket (or [10mins bus + 10 mins walk](https://goo.gl/maps/AEce3NHZZaHzHKVY6)).  We have a pre-booked set menu at 500kr/person (drinks not included), with alternatives available for dietary restrictions.

On Sunday, there will be an informal social excursion — not highly organised, mainly just a gathering-point to start off together.  If the weather is nice, we will go to [Skansen](https://www.skansen.se/en/), an open-air museum of Swedish culture and history (entrance 200kr); if it’s rainy we’ll go to [Moderna Museet](https://www.modernamuseet.se/stockholm/)/[ArkDes](https://arkdes.se/en/), a museum of modern art, architecture, and design (main collections free entry, some exhibitions charge entry).  Both options have good cafés for lunch/snacks, and other sightseeing nearby.  In either case, this is; meet at 10:00 at the main entrance (of Skansen or Moderna Museet), and take things informally from there.  We’ll announce which it is on Saturday evening!

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
