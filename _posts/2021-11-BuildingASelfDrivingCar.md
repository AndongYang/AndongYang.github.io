---
layout: post
title: Building a self-driving car
date: 2021-11
description: ..
thumbnail: assets/img/f51.png
---

Building a self-driving car that drives in the plateau environment. Participate in vehicle modification and solve the problem of no HD map, irregular path, and difficulty in manually correcting the path faced by global path planning for vehicle in plateau environment. Specific details include drawing the road network based on satellite images; Based on the generated road network and set target points, RRT* is used to generate the corresponding global path, and a visual interface based on QT is written to check and modify the planning results.


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/f51.jpeg" title="vehicle" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/f52.png" title="vehicle" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Modified vehicle.
</div>
<!-- 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/f53.png" title="software" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Global path planning software.
</div> -->
