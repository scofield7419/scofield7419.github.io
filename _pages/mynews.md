---
title: "Hao Fei - News"
layout: textlay
excerpt: "Hao Fei - News"
sitemap: false
permalink: /news
---

# News

<div style="margin-top: 20px"></div>

{% for article in site.data.news %}
<span style="font-size: 23px;">&#8226;</span> &nbsp; <strong style="font-size: 18px;">{{ article.date }}</strong><br>
{{ article.headline | markdownify}}{: .text-justify}
{% if article.photo %}{{article.photo}}{% endif %}
<div style="margin-top: 30px"></div>
{% endfor %}





