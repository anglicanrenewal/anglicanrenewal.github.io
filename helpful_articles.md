---
layout: page
title: Helpful Articles
---

## Helpful Articles[^1]

<dl>
{% for article in site.ext_articles %}
  <dt><a href="{{ article.ext_url }}">{{ article.title }}</a></dt>
  <dd>{{ article.content | markdownify }}</dd>
{% endfor %}
</dl>

---

[^1]: We think these articles are worth wrestling with as part of the conversations around
    truth, accountability, and renewal. Being in this list is not an endorsement of the
    articles and/or their authors.
