---
layout: page
title: Resources
---

## Helpful Articles

<dl>
{% for article in site.ext_articles %}
  <dt><a href="{{ article.ext_url }}">{{ article.title }}</a></dt>
  <dd>{{ article.content | markdownify }}</dd>
{% endfor %}
</dl>
