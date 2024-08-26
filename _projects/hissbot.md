---
layout: page
title: HISSbot
description: Helical Inflating Soft Snake Robot
img: assets/img/hissbot/hissbot-square.jpg
importance: 2
category: Research
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hissbot/hissbot.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    HISSbot
</div>

At the Laboratory for Robotics and Applied Mechanics of Oregon State University (OSU), I was a Research Experiences for Undergraduates Intern.
I worked with others in the lab to refine the sidewinding gait of a soft, pneumatic robot snake: HISSbot.
We compared two different actuation sequences to determine which control scheme would better reproduce gait, seen below.
We also ran experiments with multiple 3D printed flow restrictors to determine the ideal flow rate for inflating and deflating the snake. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hissbot/control-schemes.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Control Schemes
</div>

<div class="row">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hissbot/sidewinding.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/hissbot/concurrent_vs_sequential.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Sidewinding Motion: Snake (Left), Robot with Two Control Schemes (Right)
</div>

Once the movement was refined, we experimented with different material and terrains to quantify the capabilities of a soft robot snake. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hissbot/sleevings.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sleeving Materials: None (Top), Nylon (Middle), Anti-Slip Spray Coated (Bottom)
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hissbot/terrain.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Terrains: Concrete (Top), Rubber Mat (Middle), MDF (Bottom)
</div>

We tested all sleeving materials on all terrains for multiple trials but in this experimentation, we did not find any clear “best” combination.
The best terrain for each metric changed based on the sleeving material.

<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/hissbot/sample-test.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Sample Trial
</div>

Nonetheless, we proved that we could create sidewinding motion with a McKibben actuators arranged helically on a soft, snake robot.
We also provided data on the effects of flow rate, material, and terrain on the snake movement.

This work has been continued at OSU to further develop the snake.
To learn more, please see below {% cite rozaidi2023hissbot %}.


