---
layout: single
permalink: /models
title: "Models"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: https://images.unsplash.com/photo-1515524738708-327f6b0037a7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80
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
