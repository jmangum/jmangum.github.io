---
layout: page
title: Bedside Clock
description: Bedside clock that shows when the Sun is up and Moon phases
img: assets/img/BedSideClockInnards.jpg
importance: 3
category: fun
related_publications: false
---
<!--<div><h2>Bedside Clock</h2></div>-->
<!--<div><h3><a href="https://adafruit-playground.com/u/jgmangum/pages/a-neopixel-floor-lamp-with-a-twist">Neopixel LED Floor Lamp with a Twist</a></h3></div><br>-->
<div><h3>Bedside Day/Moon Phase Clock with Gesture Sensing Commands</h3></div><br>

<p>I wanted to do a project with some of the neat round displays that <a href="https://adafruit.com">Adafruit Industries</a> has been developing, so came up with this bedside clock idea.  It displays the time, synched with NTP, with a background image of the Sun when the Sun is up.  When the Sun is not up, it diaplays an image of the current Moon phase as its background.  A gesture sensor accessed through a hole in the top of the enclosure allows one to increase or decrease the backlight intensity, in the event that one wants to see what time it is in the middle of the night.  As with many of my builds, I built the enclosure out of 1/4 inch wood veneer.  ESP32-S2 microcontroller breakout board and gesture sensor from <a href="https://adafruit.com">Adafruit Industries</a>.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/PXL_20250414_002415358_muted_720p.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
