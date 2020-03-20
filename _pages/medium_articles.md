---
layout: single
permalink: /medium-articles
title: "Medium Articles"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/medium_articles.jpg
text: "Below is a list of my Medium articles. Have a read and leave me clap if you think it's any good"
articles:
  - image_path: https://cdn.pixabay.com/photo/2018/08/17/22/36/m31-3613931_960_720.jpg
    title: "Google’s EfficientDet: An Overview"
    excerpt: "Reviewing Google's EfficientDet along with the work that lead to the development to this model"
    url: "https://towardsdatascience.com/googles-efficientdet-an-overview-8d010fa15860"
  - image_path: https://cdn.pixabay.com/photo/2017/03/27/13/38/canyon-2178786_960_720.jpg
    title: "Dockerizing Python Poetry Applications"
    excerpt: "A short article on how to dockerise applications with Poetry"
    url: "https://medium.com/@harpalsahota/dockerizing-python-poetry-applications-1aa3acb76287"
  - image_path: https://cdn.pixabay.com/photo/2017/08/30/01/05/milky-way-2695569_960_720.jpg
    title: "Building a Stable and User Friendly API for your Model"
    excerpt: "Your model deserves the best API possible!"
    url: "https://towardsdatascience.com/building-a-stable-and-user-friendly-api-for-your-model-ef4b2167934e"
author: Harpal Sahota
classes: wide
---
{% if page.text %}{{ page.text }}{% endif %}
{% include feature_row id="articles" type="left" %}
