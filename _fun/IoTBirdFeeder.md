---
layout: page
title: IoT Bird (Animal) Feeder
description: A motion-activated camera catches hungry animals that visit this IoT feeder
img: assets/img/BirdFeederFront4.jpg
importance: 2
category: fun
related_publications: false
---
<script>
    document.write('<a href="' + document.referrer + '"><-- Go Back to Fun</a>');
</script><br>
<!--<div><h2>IoT Bird Feeder</h2></div>-->
<!--<div><h3><a href="https://adafruit-playground.com/u/jgmangum/pages/a-neopixel-floor-lamp-with-a-twist">Neopixel LED Floor Lamp with a Twist</a></h3></div><br>-->
<div><h3>IoT Bird (and Squirrel) Feeder with Motion Sensor-Activated Camera</h3></div><br>

<p>Built this IoT bird feeder by varying a design provided by <a href="https://learn.adafruit.com/iot-window-bird-feeder-with-camera">the Ruiz Brothers and Liz Clark at Adafruit</a>.  If you have purused any of my other electronics projects, you know that I like to use wood instead of 3D printing for my enclosures.  For my variation on this project, I used some scrap pieces of redwood.  The electronics, which includes an RP2350 Pico 2W, motion sensor, OV5640 camera breakout with SD card reader/writer, and a 2.7A LiPo battery, sits inside a hollowed-out section in the back of the feeder.  Through holes accomodate the camera and motion sensor.  When it senses motion, camera takes a picture which is uploaded to AdafruitIO and written to the onboard SD card.  Since this design is not weather-proof I strap it to my deck railing (just in case a rambunctious squirrel tries to tip it over).  I can easily get several hundred pictures a day, like the examples below.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BirdFeederFront1.jpg"  title="IoT bird feeder front" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BirdFeederFront2.jpg"  title="IoT bird feeder front (different angle)" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BirdFeederBack2.jpg"  title="IoT bird feeder back (with electronics compartment cover shown)" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BirdFeederBack1.jpg"  title="IoT bird feeder back (showing electronics compartment)" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<div class="caption" style="text-align: left;">
    Pictures of the IoT bird feeder (left-to-right): (1) Feeder from the front.  You can see the holes for the camera (smaller top hole) and motion sensor (larger bottom hole).  I used a jam jar lid that I glued to the feeder with carpet tape to hold the birdseed. (2) Animal-view of the feeder.  (3) Back of the feeder with electronics compartment cover installed.  I used a piece of 1/4 inch veneer and two window screen clasps to cover the hole that contains the electronics.  (4) Back of the feeder with electronics cover removed.  I used a piece of soft packing foam to (gently) hold the electronics in-place in the compartment.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BlueJay20250228-3.jpg"  title="Blue Jay dining on some bird seed" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Squirrel20250429-1.jpg"  title="Squirrels are frequent visitors to my IoT bird feeder" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SquirrelMoon20250429.jpg"  title="Yup...I am frequently 'mooned' by my squirrel visitors" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<div class="caption" style="left">
    <p style="text-align: left;">
    Some animals caught feeding at my IoT feeder (left-to-right): (1) A nice looking Blue Jay.  (2) A pair of squirrels are regular visitors to my IoT feeder.  This little guy will dine for more than 30 minutes at a time.  (3) Sometimes my squirrel visitors will position themselves such that they "moon" my feeder camera.  I have hundreds of such squirrel perspectives.</p>
</div>
