---
layout: page
title: project 1
description: a project for cotton water stress analysis
img: assets/img/cotton.jpg
importance: 1
category: work
---

In this project, I am using UAV-based high-resolution RGB image for cotton water stress analysis with convolutional neural networks.
<!-- It's easy to include images in a flexible 3-column grid format. -->
<!-- Make your photos 1/3, 2/3, or full width. -->

Embracing smart irrigation management techniques empowers growers to irrigate with greater efficiency, promoting sustainable agricultural production. Crop evapotranspiration is a key quantity in enabling informed irrigation decisions. The emergence of Unmanned Aerial Vehicles (UAVs), has brought about a revolutionary shift in agricultural monitoring. This project introduces a robust method for classifying water stress in cotton using a compact UAV platform and convolutional neural networks (CNN).

This research was conducted at the USDA-ARS Cropping Systems Research Laboratory (CSRL) in Lubbock, Texas, where the cotton field was divided into 12 drip zones. The study included three replications to evaluate four irrigation treatments: “rainfed”, “full irrigation”’, “percent deficit of full irrigation”, and “time delay of full irrigation”. The CNN model was able to classify the cotton water stress using UAV-based RGB images with a 91% overall best prediction accuracy.

<!-- <div class="row">
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
</div> -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cotton_field.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
