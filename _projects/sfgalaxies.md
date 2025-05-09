---
layout: page
title: Star Formation in Galaxies
description:
img: assets/img/zeta_hexmap_allReg_hatch+outline_purple.jpg
importance: 1
category: work
related_publications: true
---
<div><h2>Neural Network Constraints of the Physical Parameters of the Central Molecular Zone of NGC253</h2></div>
<div><h3><a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...977...38B/abstract" style="display:block;float:left;">Behrens et al. 2024</a></h3></div>

<p>Using a neural network-based physical and chemical model of the NGC253 central molecular zone (CMZ), Behrens etal (2024) derived the physical conditions on 50pc scales.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/allParams_hexmap_noHatch_noHeatingSrcs.jpg" title="Neural network model constraints of the physical conditions in the NGC253 central molecular zone" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div><h2>Complex Organic Molecules Towards the Central Molecular Zone of NGC253</h2></div>
<div><h3><a href="https://ui.adsabs.harvard.edu/abs/2025arXiv250419631B/abstract" style="display:block;float:left;">Bouvier et al. 2025</a></h3></div>

<p>In Galactic star-forming (SF) regions, spatial variations of interstellar complex organic molecules (iCOMs) emission could reflect the source physical structure or different chemical formation pathways. Investigating iCOMs in extragalactic star formation regions may thus provide crucial information about these regions. As an active extragalactic star formation region, the central molecular zone (CMZ) of the nearby galaxy NGC 253 provides an ideal template for studying iCOMs under more extreme conditions. This study investigates the emission of a few selected iCOMs to characterize how the differences between iCOMs are influenced by the chemical and physical structure of the NGC253 CMZ.</p>

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
