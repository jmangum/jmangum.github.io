---
layout: page
title: Star Formation in Galaxies
description: Molecular Spectral Line and Millimeter Continuum Emission
img: assets/img/zeta_hexmap_allReg_hatch+outline_purple.jpg
importance: 1
category: work
related_publications: true
---

Using the nearby starburst galaxy NGC253 as a template, I am studying how star formation influences galaxy evolution using molecular spectral line and infrared-through-radio continuum imaging measurements.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/allParams_hexmap_noHatch_noHeatingSrcs.jpg" title="Neural network model constraints of the physical conditions in the NGC253 central molecular zone" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
<a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...977...38B/abstract" style="display:block;float:left;">Behrens et al. 2024</a><br>
    Using a neural network-based physical and chemical model of the NGC253 central molecular zone (CMZ), Behrens etal (2024) derived the physical conditions on 50pc scales.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/summary_icoms_v2.jpg" title="iCOMs schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Schematic (not to scale) summarising the possible formation pathways and chemical links between iCOMs and their emission origins within a GMC.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
