---
layout: default
title: Фотографии
permalink: /album/
seo:
  type: person
---

{% assign image_files = site.static_files | where: "image", true %}
{:style="list-style-type: none;"}{% for myimage in image_files %}
  - ![Балакин Илья Владимирович]({{ myimage.path }})
{% endfor %}
