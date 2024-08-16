---
layout: default  # Keep using the current layout
title: Home
---

## Achievements

{% for achievement in site.achievements %}
- **[{{ achievement.title }}]({{ achievement.link }})**: {{ achievement.description }}
{% endfor %}
