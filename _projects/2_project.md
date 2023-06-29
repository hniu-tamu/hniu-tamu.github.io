---
layout: page
title: project 2
description: a project for evapotranspiration (ET) estimation 
img: assets/img/et.jpg
importance: 2
category: work
---

Evapotranspiration (ET) estimation is important for precision agriculture water management. Mapping the ET temporally and spatially can identify variations in the field so that it is useful for evaluating soil moisture, and assessing crop water status. ET estimation can also benefit the water resources management and weather forecast. Here I introduce one of my previous ET papers. 

The abstract is shown here:

    ---
    <p>Evapotranspiration (ET) estimation is important agricultural research in many regions because of the water scarcity, growing population, and climate change. ET can be analyzed as the sum of evaporation from the soil and transpiration from the crops to the atmosphere. The accurate estimation and mapping of ET are necessary for crop water management. One traditional method is to use the crop coefficient (Kc) and reference ET (ETo) to estimate actual ET. With the advent of satellite technology, remote sensing images can provide spatially distributed measurements. Satellite images are used to calculate the Normalized Difference Vegetation Index (NDVI). The relation between NDVI and Kc is used to generate a new Kc. The spatial resolution of multispectral satellite images, however, is in the range of meters, which is often not enough for crops with clumped canopy structures, such as trees and vines. Moreover, the frequency of satellite overpasses is not high enough to meet the research or water management needs. The Unmanned Aerial Vehicles (UAVs) can help mitigate these spatial and temporal challenges. Compared with satellite imagery, the spatial resolution of UAV images can be as high as centimeter-level. In this study, a regression model was developed using the Deep Stochastic Configuration Networks (DeepSCNs). Actual evapotranspiration was estimated and compared with lysimeter data in an experimental pomegranate orchard. The UAV imagery provided a spatial and tree-by-tree view of ET distribution.</p>
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
