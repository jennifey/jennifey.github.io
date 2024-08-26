---
layout: page
title: PosChair
description: Posture Enhancing Chair
img: /assets/img/poschair/poschair-square.png
importance: 4
category: Courses
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/poschair_callouts.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    PosChair
</div>

In my undergraduate capstone project, I collaborated with four teammates to develop the PosChair, a posture enhancing chair. 

I focused on the design and implementation of the haptic feedback system, utilizing rapid prototyping and conducting user studies to refine the system for optimal intuitiveness. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/haptics.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Haptic Feedback System
</div>

We integrated posture detection using infrared sensors to detect back angle. 
We initially used ultrasonic sensor but found the results to be too noisy.
We also implemented weight distribution detection with load cells.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/back-p1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/loadcell-p1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Initial Prototypes: Back Position with Ultrasonic Sensor (Left), Weight Distribution Load Cell (Right)
</div>

The haptic feedback system was supplemented with a visual feedback system for both the sensing systems.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/back-vis.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/weight-vis.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Initial Prototypes: Back Position with Ultrasonic Sensor (Left), Weight Distribution Load Cell (Right)
</div>

These systems were all packaged into a chair as our final prototype.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/prototype.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Final Project Poster
</div>

The prototype’s safety was rigorously tested through thermal, stress, battery life, and material analyses. 
Additionally, we prepared a mass-manufacturing plan with a cost estimate and performed failure mode and life cycle analyses. 
Our final prototype received positive feedback from users, validating the effectiveness of our design.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/poschair/poster.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Final Project Poster
</div>

To learn more about this project, please see the final report.

<div class="post">
    <header class="post-header">
      <h1 class="post-title">
        PosChair Final Report
          <a
            href="/assets/pdf/PostureChair_Final_Report.pdf"
            target="_blank"
            rel="noopener noreferrer"
            class="float-right"
            ><i class="fa-solid fa-file-pdf"></i
          ></a>
      </h1>
    </header>
</div>
