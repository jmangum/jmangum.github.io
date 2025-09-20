---
layout: page
title: A CAN Bus-Based Home Sensor Network
description: Ever wondered what to do with that old twisted-pair phone cable running throughout your house?
img: assets/img/PhoneCANNode1.jpg
importance: 4
category: fun
related_publications: false
---
<!--<div><h2>CAN-Bus Home Sensor Network</h2></div>-->
<div><h3><a href="https://adafruit-playground.com/u/jgmangum/pages/home-can-bus-network-using-telephone-wiring">Home CAN Bus Networking Using Telephone Wiring</a></h3></div>

<p>Have you ever wondered what you can do with your unused twisted-pair telephone wire running throughout your house? Well, how about using it as the transport medium for a CAN bus network of environmental sensors? This project, which I dubbed PhoneCAN, is a relatively easy project which uses Adafruit hardware and CiruitPython.  My setup uses four CAN nodes.  Check-out the link above for my detailed design in the Adafruit Playground.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PhoneCANNode2.jpg" title="One of the CAN bus nodes in my home sensor network." class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PhoneCANNode1.jpg" title="CAN bus node showing connection to one of the phone jacks in my house." class="img-fluid rounded z-depth-1"%} 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PhoneCANNode3.jpg" title="Another CAN bus node on my network.  I include backup LiPo batteries for all nodes to smooth over power failures." class="img-fluid rounded z-depth-1"%} 
    </div>
</div>
<div class="caption" style="left">
    Pictures of my phone line-based CAN bus network nodes.  Left-to-right: (1) I incorporated an display on one of my nodes to display current measurements for that node.  (2) Shows how the CAN node connects to my home phone line wiring.  (3) Another CAN node on my network.  I in corporated LiPo batteries to serve as power backup.
</div>
