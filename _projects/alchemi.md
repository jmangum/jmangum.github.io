---
layout: page
title: The ALma Comprehensive High-resolution Extragalactic Molecular Inventory (ALCHEMI)
description:
img: assets/img/NGC253-HCNIntPanel.jpg
importance: 2
category: work
related_publications: false
---
<script>
    document.write('<a href="' + document.referrer + '"><-- Go Back to Research Projects</a>');
</script><br>

<div><h2>The ALCHEMI ALMA Large Programme</h2></div>
<div class="publications">
  {% bibliography -f papers -q @*[topic~=alchemi]* %}
</div>
<div><h3><a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...977...38B/abstract" style="display:block;float:left;">Behrens et al. 2024</a></h3></div><br>

<p>Using a neural network-based physical and chemical model of the NGC253 central molecular zone (CMZ), Behrens etal (2024) derived the physical conditions on 50pc scales.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/allParams_hexmap_noHatch_noHeatingSrcs.jpg" title="Neural network model constraints of the physical conditions in the NGC253 central molecular zone" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
