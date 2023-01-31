---
title: "News"
layout: textlay
excerpt: "Cameron Calk."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br />
<em>{{ article.headline | markdownify}}</em>
{% endfor %}
