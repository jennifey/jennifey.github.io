---
layout: page
title: Beanbag Pick and Place
description: Pick and Place Network for Deformable Objects
img: /assets/img/beanbag/robot-square.jpeg
importance: 3
category: Courses
---

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/beanbag/robot-square.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Franka Robot with Parallel Gripper for Beanbag Pick and Place
</div>

For the final project for Learning for Manipulation, In a team of four, I worked on a pick-and-place model for deformable objects like beanbags. 
We employed behavior cloning with a modified transporter network on a Franka robot arm with a parallel gripper. 

We first ran the original transporter network in simulation, resulting in 100% testing accuracy.
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/beanbag/simulation-results.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Simulation Results
</div>

Then we switched to real-world deployment.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/beanbag/rw-dev.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Real World Deployment Process
</div>

I developed an automated data collection system that utilized RGB images and camera calibration with color masking to identify approximate grasping locations. 
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/beanbag/data-col.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Data Collection Process
</div>

We trained the transporter network on this dataset to predict robot grasp positions with high accuracy.
We demonstrated that the robot is able to handle deformable objects effectively and implicitly learn the camera calibration in the process.
We were able to place the beanbag on both virtually annotated positions and annotated positions in the real world.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/beanbag/virtual-results.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/beanbag/real-results.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Robot Deployment Results: Virtual Annotation (Top), Real Annotation (Bottom)
</div>

Although there was placing inaccuracies, this could be improved with further with more higher quality data to improve the model.

To learn more about this project, please see the final paper.

<div class="post">
    <header class="post-header">
      <h1 class="post-title">
        BeanBag Pick and Place Final Paper
          <a
            href="/assets/pdf/16_740_final_report.pdf"
            target="_blank"
            rel="noopener noreferrer"
            class="float-right"
            ><i class="fa-solid fa-file-pdf"></i
          ></a>
      </h1>
    </header>
</div>