---
layout: default
title: Видео из Telegram
permalink: /videos/
seo:
  type: person
videos:
  - video1.mp4
  - video2.mp4
  - video3.mp4
  - video4.mp4
  - video5.mp4
---

{: style="font-weight:bold;"}{% for video in page.videos %}
  <video controls><source src="https://raw.githubusercontent.com/ilyasik2015/ilyasik2015.github.io/master/assets/video/{{ video }}" type="video/mp4">Your browser does not support the audio tag. [Download {{ video }}](https://raw.githubusercontent.com/ilyasik2015/ilyasik2015.github.io/master/assets/video/{{ video }})</video><br/>
{% endfor %}
