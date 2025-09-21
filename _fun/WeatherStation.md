---
layout: page
title: Weather Station
description: My first electronics project, and still my favorite
img: assets/img/WeatherDisplayUS.jpg
importance: 6
category: fun
related_publications: false
---
<script>
    document.write('<a href="' + document.referrer + '">Go Back to Fun</a>');
</script><br>
<!--<div><h2>Weather Station</h2></div>-->
<!--<div><h3><a href="https://adafruit-playground.com/u/jgmangum/pages/a-neopixel-floor-lamp-with-a-twist">Neopixel LED Floor Lamp with a Twist</a></h3></div><br>-->
<div><h3>Home Weather Station</h3></div><br>

<p>This was the first electronics project that I built, and it is still my favorite.  Now on version 0.2, the design (version 0.0) was based on a Raspberry Pi 3B that was powered with a recharagable 12A LiPo battery connected to a 6W solar panel.  That configuration was hard to keep running in the winter (with much less daylight), so I converted it to a Feather M0 (from <a href="https://adafruit.com">Adafruit Industries</a>) based design.  Uses packet radio (RFM95) to send weather measurements to a Raspberry Pi 3B in my house every 20 seconds or so.  Those measurements are then stored in a MySQL database and pushed out to the internet (Weather Underground and NWS Citizens Weather Observer Program) and a local display (via RFM95 packet radio) that I built.  Will eventually post the detailed design to the Adafruit Playground.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/WeatherDisplayUS.jpg" title="Weather measurement display (US units)." class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/WeatherDisplayMetric.jpg" title="Weather measurement display (metric units)." class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/WeatherDisplayAlt.jpg" title="Weather measurement display (alternate measurements that I could not fit on either of the other two displays, such as ground temperature)." class="img-fluid rounded z-depth-1"%} 
    </div>
</div>
<div class="caption" style="left">
    Pictures of my home weather sensor system measurement display.  Left-to-right: (1) Weather sensor measurements in US units.  (2) Weather sensor measurements in metric units.   (3) Weather sensor measurements that could not fit on either the US or metric display, such as measurements from a ground temperature sensor.
</div>
