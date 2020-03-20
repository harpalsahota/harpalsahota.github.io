---
layout: single
permalink: /visualisations
title: "Models"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: https://images.unsplash.com/photo-1515524738708-327f6b0037a7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80
text: "Over the years I've developed a few models, below is a list of them which are deployed and free to use"
visualisations:
  - image_path: assets/images/daylight_hours.png
    title: "Daylight Hours"
    excerpt: "An animation to show how the hours of daylight changes as a function of latitude and day of year"
    url: "https://www.drdatascience.co.uk/portfolio/daylight-hours"
  - image_path: assets/images/life_expectancy.png
    title: "Life Expectancy"
    excerpt: "The difference in life expectancy between men and woman from various countries overtime"
    url: "https://www.drdatascience.co.uk/portfolio/life-expectancy"
  - image_path: assets/images/formula_1_champions.png
    title: "Formula 1 World Champions"
    excerpt: "A breakdown of all F1 world champions by their nationality"
    url: "https://www.drdatascience.co.uk/portfolio/f1-world-champions"
  - image_path: assets/images/tracing_web_requests.png
    title: "Tracing Web Requests"
    excerpt: "Tracing web requests from some of the worlds most popular websites"
    url: "https://www.drdatascience.co.uk/portfolio/tracing-web-requests"
  - image_path: assets/images/conways_game_of_life.png
    title: "Conway's Game Of Life"
    excerpt: "Visualising Conway's game Of life"
    url: "https://www.drdatascience.co.uk/portfolio/conways-game-of-life"
author: Harpal Sahota
---
{% if page.text %}{{ page.text }}{% endif %}
{% include feature_row id="visualisations" type="left" %}
