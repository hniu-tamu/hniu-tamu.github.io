---
layout: page
title: project 1
description: a project for cotton water stress analysis
img: assets/img/cotton.jpg
importance: 1
category: work
---

The emergence of Unmanned Aerial Vehicles (UAVs), has brought about a revolutionary shift in agricultural monitoring. This project introduces a robust method for classifying water stress in cotton using a compact UAV platform and convolutional neural networks (CNN). Embracing smart irrigation management techniques empowers growers to irrigate with greater efficiency, promoting sustainable agricultural production. Crop evapotranspiration is a key quantity in enabling informed irrigation decisions.

This research was conducted at the USDA-ARS Cropping Systems Research Laboratory (CSRL) in Lubbock, Texas, where the cotton field was divided into 12 drip zones. The study included three replications to evaluate four irrigation treatments: “rainfed”, “full irrigation”’, “percent deficit of full irrigation”, and “time delay of full irrigation”. The CNN model was able to classify the cotton water stress using UAV-based RGB images with a 91% overall best prediction accuracy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cotton_field.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The experimental field for cotton water stress analysis.
</div>

To classify the cotton water stress with CNN models, the large scale of UAV cotton image was splitted into smaller scales with ArcGIS Pro and python, which created thousands of images for each sampling date. The following figure is a demonstration of how the new dataset looks like. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0 d-flex align-items-center justify-content-center">
        {% include figure.html path="assets/img/cotton_small.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Our draft paper is under review. More details will be shared once the paper is published.