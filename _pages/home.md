---
layout: single
permalink: /
title: "Harpal Sahota"
subtitle_about_me: "About Me"
subtitle_skills: "My Skills"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header_image.jpg
excerpt: "Data Scientist &#124; Developer &#124; Visualiser &#124; Tech Support for Mum and Dad"
text_about_me: "Welcome to my Github page! Feel free to browse my portfolio and have a read of my blogs. Below are some of my top skills I’ve developed over the years as a Data Scientist"
programming:
  - image_path: https://img.icons8.com/color/512/000000/python.png
  - image_path: https://img.icons8.com/color/480/000000/javascript.png
  - image_path: https://img.icons8.com/color/480/000000/c-programming.png
ai:
  - image_path: /assets/images/sklearn_logo.png
  - image_path: /assets/images/pytorch_logo.png
  - image_path: /assets/images/tensorflow_logo.png
web_dev:
  - image_path: https://raw.githubusercontent.com/d3/d3-logo/master/d3.png
  - image_path: https://img.icons8.com/color/480/000000/angularjs.png
  - image_path: /assets/images/flask_logo.png
development:
  - image_path: https://img.icons8.com/nolan/512/github.png
  - image_path: https://img.icons8.com/color/480/000000/docker.png
  - image_path: https://img.icons8.com/color/480/000000/kubernetes.png
  - image_path: /assets/images/aws_logo.png
author: Harpal Sahota
---
<h3>{% if page.subtitle_about_me %}{{ page.subtitle_about_me }}{% endif %}</h3>
{% if page.text_about_me %}{{ page.text_about_me }}{% endif %}
<h2>{% if page.subtitle_skills %}{{ page.subtitle_skills }}{% endif %}</h2>
{% include feature_row id="programming" %}
{% include feature_row id="ai" %}
{% include feature_row id="web_dev" %}
{% include feature_row id="development" %}
