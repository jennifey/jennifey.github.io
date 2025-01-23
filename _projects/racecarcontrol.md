---
layout: page
title: Optimized Racecar Control
description: Quadratic Optimization-Based Controller for Carnegie Mellon Racing 24e
img: /assets/img/robomath/car-square.jpg
importance: 2
category: Courses
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/robomath/car.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Carnegie Mellon Racing's 22e Vehicle
</div>

I worked with 2 teammates on developing a cost-optimized control pipeline for Carnegie Mellon Racing as my final project for Math Fundamentals for Robotics.

The original pipeline was a sequential set of controllers that have conflicting goals. 
Each controller returns its optimal solution, but final solution isn’t necessarily the optimal combination of solutions.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/robomath/naive_pipeline.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Original Pipeline
</div>

The optimized pipeline produced 4-wheel torque-vectored results that are optimized across all the vehicle constraints. 
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/robomath/osqp_pipeline.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Optimized Pipeline
</div>

The simulations demonstrate a 90% improvement on reaching the target yaw moment while maintaining a less than 5% impact on realized linear acceleration and power consumption. 
This pipeline is currently being further developed by Carnegie Mellon Racing for use on future vehicles.

To learn more about this project, please see the final paper.

<div class="post">
    <header class="post-header">
      <h1 class="post-title">
        Optimized Racecar Control Final Paper
          <a
            href="/assets/pdf/16811_Final_Project.pdf"
            target="_blank"
            rel="noopener noreferrer"
            class="float-right"
            ><i class="fa-solid fa-file-pdf"></i
          ></a>
      </h1>
    </header>
</div>