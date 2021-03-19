---
title: Archived Satellite Images
permalink: /archives/satellite_images
description: All the satellite images taken with handmade antenna
---

# NOAA Satellite Images

These images are NOAA satellite images captured using my software defined radio (SDR) and [GQRX](https://gqrx.dk/).
NOAA satellites use a protocol called [automatic picture transmission (APT)](https://en.wikipedia.org/wiki/Automatic_picture_transmission), which I decode using [noaa-apt](https://noaa-apt.mbernardi.com.ar/).

I modeled the antenna that I'm using and 3d-printed the arms to make sure they are at the correct height. The model is shown here, click it to access the onshape project.

<a href="https://cad.onshape.com/documents/417c949b1c400718ad9f1661/w/05aeb523f63297d16f2649be/e/5144a1f2b6e79a66b5c89203"> <img src="/assets/images/archive/DoubleCrossDipole.png" alt="Image of the Double Cross Dipole Antenna"> </a>

And I used it to create what's seen below.

<img src="/assets/images/archive/RealAntenna.png" alt="Image of antenna built up" style="height:500px;width:500px;">

<img src="/assets/images/archive/Closeup.png" alt="Image of closeup of the antenna" style="height:500px;width:500px;">

And here are the satellite images that I've captured. Most of them are fuzzy and not very good, but some are pretty cool and I'd like to keep track of them all.

<ul>
{% for image in site.static_files reversed %}
    {% if image.path contains 'images/satellite_images' %}
        <a href="{{ site.baseurl }}{{ image.path }}" class="js-smartphoto" data-caption="{{ image.name }}" data-id="{{ image.name }}" data-group="1">
            <img src="{{ site.baseurl }}{{ image.path }}" />
        </a>
    {% endif %}
{% endfor %}
</ul>


<link rel="stylesheet" href="../assets/css/smartphoto.min.css">
<script src="../assets/js/smartphoto.min.js"></script>
<script>
document.addEventListener('DOMContentLoaded',function(){
  new SmartPhoto(".js-smartphoto");
});
</script>
