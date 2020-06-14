---
title: Archived Satellite Images
permalink: /archives/satellite_images
description: All the satellite images taken with handmade antenna
---

# NOAA Satellite Images

These images are NOAA satellite images captured using my software defined radio (SDR) and [GQRX](https://gqrx.dk/).
NOAA satellites use a protocol called [automatic picture transmission (APT)](https://en.wikipedia.org/wiki/Automatic_picture_transmission), which I decode using [noaa-apt](https://noaa-apt.mbernardi.com.ar/).

This is my archive of satellite images that I've captured. Most of them are fuzzy and not very good, but some are pretty cool and I'd like to keep track of them all.

<ul>
{% for image in site.static_files reversed %}
    {% if image.path contains 'images/satellite_images' %}
        <h3>{{ image.name }}</h3>
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
</ul>
