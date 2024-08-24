---
layout: page
title: DeltaWalker
description: Soft, Linearly Actuated Delta Quadruped Robot
img: assets/img/deltawalker/deltawalker.jpg
importance: 1
category: Research
related_publications: true
---

The DeltaWalker is a soft, linearly actuated delta quadruped robot that is capable of omnidirectional walking and rotating in palce

To read my complete thesis document, please see below {% cite Yang-2024-142602 %}.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/walker-demo.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    DeltaWalker Demo
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/walk-manual-sim.mp4" class="img-fluid rounded z-depth-1" controls=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/walk-trajop-sim.mp4" class="img-fluid rounded z-depth-1" controls=true%}
    </div>
</div>
<div class="caption">
    Simulation For Walk Gait with Step Size 1 cm: Manually Designed (Left) vs Trajectory Optimized (Right)
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/sgait-manual-sim.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/sgait-trajop-sim.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Simulation For S-Gait Gait with Step Size 1 cm: Manually Designed (Left) vs Trajectory Optimized (Right)
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/walk-manual-exp.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/walk-trajop-exp.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Experiment For Walk Gait with Step Size 1 cm: Manually Designed (Left) vs Trajectory Optimized (Right)
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/sgait-manual-exp.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/sgait-trajop-exp.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Experiment For S-Gait Gait with Step Size 1 cm: Manually Designed (Left) vs Trajectory Optimized (Right)
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/rotation.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Rotation in Place 15 Degrees 3 Times for a Total Rotation of 45 Degrees
</div>