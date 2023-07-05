---
title: "Hao Fei - Publications"
layout: textlay
excerpt: "Hao Fei -- Publications."
sitemap: false
permalink: /publications
---


# Publications


`#` denotes equal contribution, `*` denotes correspondence.
See full publications in [Google Scholar](https://scholar.google.com/citations?user=YGDX46AAAAAJ). <br>
Jump to [Preprint](#preprint), [Conference](#conference), [Journal](#journal), [Others](#others).


<div style="margin-top: 20px"></div>

### &#9654; Preprint<a name="preprint" />

{% for publi in site.data.pub_preprint %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>{{ publi.venue.name }}</strong> &nbsp;&nbsp; {{ publi.year }} &nbsp;&nbsp;&nbsp;&nbsp; <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}&nbsp;{% if publi.promote %}<a href="{{ publi.promote.link }}">\[{{ publi.promote.name }}\]</a>{% endif %}

{% endfor %}





<div style="margin-top: 30px"></div>


### &#9654; Conference<a name="conference" />

{% for publi in site.data.pub_conference %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>{{ publi.venue.name }}</strong>     {% if publi.venue.note %} ({{publi.venue.note}}){% endif %} &nbsp;&nbsp; {{ publi.year }} 
 {% if publi.highlight %}&nbsp;&nbsp;&nbsp;&nbsp;   <strong style="color:#C7254E;">({{ publi.highlight }})</strong>  {% endif %} &nbsp;&nbsp;&nbsp;&nbsp; <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}&nbsp;{% if publi.promote %}<a href="{{ publi.promote.link }}">\[{{ publi.promote.name }}\]</a>{% endif %}

{% endfor %}





<div style="margin-top: 30px"></div>

### &#9654; Journal<a name="journal" />

{% for publi in site.data.pub_journal %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ publi.venue.full }} {% if publi.venue.short %}(<strong>{{publi.venue.short}}</strong>){% endif %} &nbsp;&nbsp; {{ publi.year }}&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}

{% endfor %}





<div style="margin-top: 30px"></div>

### &#9654; Others<a name="others" />


{% for publi in site.data.pub_other %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>{{ publi.venue.name }}</strong> {% if publi.venue.note %} ({{publi.venue.note}}){% endif %} &nbsp;&nbsp; {{ publi.year }}&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}

{% endfor %}

