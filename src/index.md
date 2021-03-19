---
title: my first eleventy site
layout: base.njk
---

## My amazing thoughts

I wish they had a drug that made you curious about things, like I wish I was curious about build tools. They are very convoluted. Thanks bye.

![cat of the day]({{ catpic }})

{% for page in collections.pages %}

- [{{ page.data.title }}]({{ page.url }})
  {%- endfor %}
