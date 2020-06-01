---
title: Archived Satellite Images
permalink: /archives/satellite_images
---

# NOAA Satellite Images

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'images/satellite_images' %}
        <h3>{{ image.name }}</h3>
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
</ul>