---
layout: single
permalink: /models
title: "Models"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/medium_articles.jpg
text: "Over the years I've developed a few models, below is a list of them which are deployed and free to use"
deployed_models:
  - image_path: https://img.icons8.com/nolan/512/steam.png
    title: "Steam Game Recommender"
    excerpt: "A Steam game recommender with a slight difference in that you can customise your recommendations"
    url: "http://ec2-18-202-21-30.eu-west-1.compute.amazonaws.com/"
author: Harpal Sahota
---
{% if page.text %}{{ page.text }}{% endif %}
{% include feature_row id="deployed_models" type="left" %}
