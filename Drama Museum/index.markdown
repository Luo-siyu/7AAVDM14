---
title: Little Life in Drama
layout: index
---

{% for exhibit in site.exhibits %}

<img src="{{ exhibit.image-url }}" width = 256>
<p>{{ exhibit.title }} by {{ exhibit.writer }} </p>

{% endfor %}