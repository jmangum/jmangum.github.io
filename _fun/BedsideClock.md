---
layout: page
title: Bedside Clock
description: Bedside clock that shows when the Sun is up and Moon phases
img: assets/img/BedSideClockDay1.jpg
importance: 3
category: fun
related_publications: false
---
<script>
    document.write('<a href="' + document.referrer + '">Go Back to Fun</a>');
</script><br>
<!--<div><h2>Bedside Clock</h2></div>-->
<!--<div><h3><a href="https://adafruit-playground.com/u/jgmangum/pages/a-neopixel-floor-lamp-with-a-twist">Neopixel LED Floor Lamp with a Twist</a></h3></div><br>-->
<div><h3>Bedside Day/Moon Phase Clock with Gesture Sensing Commands</h3></div><br>

<p>I wanted to do a project with some of the neat round displays that <a href="https://adafruit.com">Adafruit Industries</a> has been developing, so came up with this bedside clock idea.  It displays the time, synched with NTP, with a background image of the Sun when the Sun is up.  When the Sun is not up, it diaplays an image of the current Moon phase as its background.  A gesture sensor accessed through a hole in the top of the enclosure allows one to increase or decrease the backlight intensity, in the event that one wants to see what time it is in the middle of the night.  As with many of my builds, I built the enclosure out of 1/4 inch wood veneer.  ESP32-S2 microcontroller breakout board and gesture sensor from <a href="https://adafruit.com">Adafruit Industries</a>.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BedSideClockDay1.jpg" title="Bedside clock front view during daytime" class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BedSideClockDay3.jpg" title="Bedside clock front view in daytime, showing enclosure" class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BedSideClockMoon1.jpg" title="Bedside clock in action (night view)" class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BedSideClockInnards.jpg" title="Bedside clock innards (ESP32-S3 and gesture sensor)" class="img-fluid rounded z-depth-1"%} 
    </div>
</div>
<div class="caption" style="left">
    Pictures and a movie of my bedside clock.  Left-to-right: (1) Bedside clock as it appears during the day.  (2) Daytime view from another angle to show enclosure and gesture sensor access (hole in top of enclosure).  (3) Night time view.  (4) Bedside clock innards (ESP32-S3 and gesture sensor).
</div>

