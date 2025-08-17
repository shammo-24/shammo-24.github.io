---
layout: page
title: modeling cable-driven soft robots
description:
img: assets/img/thumb-JMR.jpg
importance: 2
category: Current
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/soro-1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Tendon-driven soft robotic systems draw inspiration from the muscular-skeletal systems of animals wherein the way tendons connect muscles to bones in living organisms, enables precise control of movement. 

In literature, the computational modeling for such systems have been limited to piecewise constant curvature (PCC), cosserat rod-based or geometric variable strain (GVS) methods. Although being computationally inexpensive, the underlying assumptions in such methods might restrict us to utilize them for any generalized geometry. Moreover, there lies a gap in the literature in term of a high fidelity computational modeling framework for tendon-driven soft robots. 

We contribute to this field by introducing a finite element method (FEM)-based full fledged computational modeling framework for tendon-driven soft robotic systems. Utilizing the powerful python scripting ability of the FEM framework ABAQUS, we are modeling tendon-driven soft actuators and manipulators. We plan on validating the numerical results experimentally by using a point cloud capture method. The ultimate goal of this work is to assess the ability of our modeling framework in solving an inverse design problem related to tendon-driven soft robots.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid loading="eager" path="assets/video/Mani.mp4" title="example video" class="img-fluid rounded z-depth-1" controls=true muted=true autoplay=true loop=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid loading="eager" path="assets/video/Loco.mp4" title="example video" class="img-fluid rounded z-depth-1" controls=true muted=true autoplay=true loop=true %}
    </div>
</div>
<div class="caption">
    Left to Right: Manipulator workspace and locomotive actuator workspace.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid loading="eager" path="assets/video/complx.mp4" title="example video" class="img-fluid rounded z-depth-1" controls=true muted=true autoplay=true loop=true %}
    </div>
    <!-- <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid loading="eager" path="assets/video/Octo.mp4" title="example video" class="img-fluid rounded z-depth-1" controls=true muted=true height="200px" autoplay=true %}
    </div> -->
</div>
<div class="caption">
    Left to Right: Modeling non-uniform actuator geometries - Trapezoidal shape and Elephant-trunk inspired tapered-cylindrical shape.
</div>

Our model not only captures simple uniform geoemtries, but also non-uniform geometries which are difficult to model using the existing reduced-order formulations. Below flowchart showcases the overall pipeline for model validation, which utilizes point cloud-based data capture and shape-centric metrics for sim2real comparison. Read more about this framework in my <a href="https://doi.org/10.1115/1.4069292">ASME JMR publication</a>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/soro-2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    (a)-(b) Coefficient of friction calculation, (c)-(d) Validation test set-up, and (e) validation flowchart
</div>

<!-- 
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

{% endraw %} -->
