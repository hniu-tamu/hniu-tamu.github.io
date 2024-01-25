---
layout: page
title: project 2
description: a project for evapotranspiration (ET) estimation 
img: assets/img/et.jpg
importance: 2
category: work
---

Evapotranspiration (ET) estimation is important for precision agriculture water management. Mapping the ET temporally and spatially can identify variations in the field so that it is useful for evaluating soil moisture, and assessing crop water status. ET estimation can also benefit the water resources management and weather forecast. 

Limited water supplies, increasing pumping costs, variable rainfall patterns, and competition with municipalities are some of the challenges faced by agricultural communities across the state. Consequently, timely delivery and efficient use of irrigation water are critical to the sustainability and long-term stability of agricultural production in Texas. Presently, irrigation scheduling decisions based on reference evapotranspiration (ET) are limited due to the lack of reliable and readily available in-field weather data and updated crop coefficients. Additionally, information about in-field variability of crop water demand is seldom considered in the decision-making process. As a result, the efficiency of irrigation is often low, which leads to wasteful use of water in areas that are already plagued by scarce water resources.

In this project, we propose the development of an Unmanned Aerial System (UAS) based crop monitoring system that calculates crop water use for irrigation scheduling and increased water use efficiency. To do this, our system will take the advantage of big data analytics and Artificial Intelligence (AI) on the UAS-derived phenotypic data and infield weather data to calculate actual crop evapotranspiration, biomass accumulation, and determine the timing and quantity of irrigation water needed.




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
