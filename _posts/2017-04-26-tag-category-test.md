---
layout: post
title: Is this potato working
category: Potato
tags: ["testtag1", "tasttag2"]
---

{% if page.tags %} | 
  {% for tag in page.tags %}
    <a href="{{ site.baseurl }}{{ site.tag_page }}#{{ tag | slugify }}" class="post-tag">{{ tag }}</a>
  {% endfor %}
{% endif %}


Please work, it would be really nice if it did.



