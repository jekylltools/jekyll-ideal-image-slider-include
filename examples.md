---
layout: page
title: Examples
permalink: /examples/
image_sliders:
  - slider1
  - slider2
  - slider3
---

[View the Markdown source for this page](https://raw.githubusercontent.com/jekylltools/jekyll-ideal-image-slider-include/gh-pages/examples.md)

[View the slider settings in `_data/sliders.yml`](https://github.com/jekylltools/jekyll-ideal-image-slider-include/blob/gh-pages/_data/sliders.yml)

## slider 1

settings for this slider taken from [Ideal-Image-Slider-JS#getting-started](https://github.com/Codeinwp/Ideal-Image-Slider-JS#getting-started)

{% include slider.html selector="slider1" %}

## slider 2

same images, different settings.

{% include slider.html selector="slider2" %}

## slider 3

same images, minimal settings, no bullets, no captions, no navigation

{% include slider.html selector="slider3" %}
