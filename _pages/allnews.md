---
title: "Home"
layout: textlay
excerpt: "Mitch Daniel in the Hughes lab at Florida State University"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
