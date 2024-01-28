---
layout: page
title: project 5
description: a project for image segmentation
img: assets/img/mask.jpg
importance: 5
category: work
---

The development of sensors and cameras has made it convenient to obtain images with higher resolution at a very low cost for precision agriculture applications. This has led to improved high-throughput phenotyping. Within perennial crops, canopy size can help estimate water use, yield and pesticide requirements. Typically, one of the widely used methods is to estimate the canopy size by 3D point-cloud data collected using Light Detection and Ranging or LIDAR. However, LIDAR‘s usage is limited because of the high cost and complicated post-processing procedures. There is also other method which estimates canopy size by using 2D images. Canopy classification and detection can be based on artificial features, such as threshold determination, shape and compactness. These features are very specific, however, which renders the approach to small changes in the objects, backgrounds or camera settings. To overcome these limitations, we proposed to classify and differentiate canopy pixels of pomegranate trees by using a fully convolutional neural network, called instance-aware semantic segmentation. Not only can it classify canopy pixels from pixels of soil and grass, but also differentiate canopy pixels between neighboring trees. Tests on validation set showed that its precision reached above 90% and it is robust to changes in camera setting, lighting condition, canopy development and changing background.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 d-flex align-items-center justify-content-center">
        {% include figure.html path="assets/img/segmentation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
