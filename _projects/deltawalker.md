---
layout: page
title: DeltaWalker
description: Soft, Linearly Actuated Delta Quadruped Robot
img: assets/img/deltawalker/deltawalker.jpg
importance: 1
category: Research
related_publications: true
---

<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/deltawalker.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    DeltaWalker
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/walker/walker-demo.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    DeltaWalker Demo
</div>

### About This Project ###

This work is for the completion of my Master of Science in Robotics Degree. 
It is associated with the [Zoom Lab](https://www.ri.cmu.edu/robotics-groups/zoom-lab/) at Carnegie Mellon University, led by [Prof. Zeynep Temel](https://www.ri.cmu.edu/ri-faculty/zeynep-temel/).

To read my complete thesis document, please see below {% cite Yang-2024-142602 %}.

To view the code for this project, please visit the [GitHub Repository](https://github.com/ZoomLabCMU/DeltaWalker).

For more demo videos, please see [here](https://drive.google.com/drive/folders/1xwSiLlWAuQjfcfQEBsLWVnv6Q9RkXis3?usp=sharing).

### Abstract ###
Quadruped robots offer a versatile solution for navigating complex terrain, making them valuable for applications such as industrial automation or search and rescue. Although quadrupeds are more complex than bipeds, they are easier to balance and control and require fewer joints to actuate compared to hexapods. Traditional quadruped designs, however, often feature complex leg mechanisms that are difficult to scale and require many actuators.

We introduce the DeltaWalker, a novel quadruped robot that uses linearly actuated Delta robots as legs. Delta robots offer advantages such as precision and scalability, while still being able to move with three degrees of freedom. This design is inspired by DeltaHands, a 4-fingered hand robot with soft, 3D-printed linear Delta robots. We turn the DeltaHands upside down and adapt the design for locomotion. We explore various gait patterns, including manually designed and trajectory-optimized gaits, evaluated in both simulated and real-world environments. We also describe the system kinematics and investigate other capabilities, such as rotating in place. The findings from these evaluations demonstrate the potential of the DeltaWalker as a simpler, scalable, omnidirectional quadruped robot.

### Project Details ###

I developed the DeltaWalker, a novel quadruped robot that uses soft, linearly actuated Delta robots as legs.
Each Delta has 3 translational degrees of freedom, allowing the robot to move omnidirectionally or rotate in place.
It is small scale, weighing 570 grams. It is approximately 15 cm x 15 cm x 18 cm.
It is also low cost, with materials costing less than $800 in total.
The design is modularized into the following primary components: legs, feet, shoes, frames, spacers, actuators, and PCB.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/walker-components.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    DeltaWalker Components
</div>

Due to the omnidirectional nature of the robot, I designed two different orientations for the robot: 
Front/Back (FB) Orientation and Front/Back/Side (FBS) Orientation. T
This allows for even more flexibility with the robot locomotion.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/orientation-diagram.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Orientation Guide
</div>

I used two methods for designing the trajectories: manually and with trajectory optimization.
Specifically, I used non-linear trajectory optimization techniques to generate cost-optimized trajectories that accounted for the system’s physical, geometric, and dynamics constraints.
These trajectory optimized gaits were generated with multiple step sizes.
The FB Orientation gaits are Walk and Amble.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/fb-gaits-gen.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    FB Orientation Gaits: Walk (Top), Amble (Bottom)
</div>

The FBS Orientation gaits are S-Gait and C-Gait.
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/fbs-gaits-gen.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    FBS Orientation Gaits: S-Gait (Top), C-Gait (Bottom)
</div>

I tested these gaits with a simulation model of the robot that I built.
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/12act-urdf.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    DeltaWalker Simulation Model
</div>

I also ran experiments on the physical robot. 
I used color detection to track the position of each of the feet, quantifying the robot performance and error.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deltawalker/processed.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    DeltaWalker Experiments: Video Processing with Color Detection for Data Analysis
</div>

The manually designed gaits were highly inaccurate with respect to the desired foot positions. 
However, the trajectory-optimized gaits were fairly accurate. 
Walk and S-Gait are better suited towards larger steps
Amble and C-Gait are better suited towards smaller steps

**Ultimately, I introduced a novel quadruped robot capable of walking and rotating in place. 
I also introduced a simulation model and physical model of the robot. 
I was able to generate multiple trajectories with different foot orders by utilizing trajectory optimization.
And I was able to identify which step sizes were best suited for each gait.**
