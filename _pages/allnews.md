---
title: "News"
layout: textlay
excerpt: "Davuluri Lab at Stony Brook University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }}</p> <br>
<p><em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
