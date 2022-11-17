---
title: "News"
layout: textlay
excerpt: "Digital One Health - University of Edinburgh"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
**{{ article.date }}**
{{ article.headline | markdownify}}
{% endfor %}

<!--

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}

-->
