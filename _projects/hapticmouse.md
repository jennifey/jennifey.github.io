---
layout: page
title: Haptic Mouse
description: Haptic Mouse to Enhance Learning Experiences for Visually Impaired Users
img: assets/img/mouse/ergomouse-square.jpg
importance: 1
category: Courses
---

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mouse/mouse-square.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mouse/ergomouse-square.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Haptic Mouse: Current Edition (Left), Next Edition with Ergonomic Grip (Right)
</div>

For my final project for Engineering Haptic Interfaces, I worked with four teammates to develop the Haptic Mouse
This is an assistive device designed to enhance mathematical learning for visually impaired students. 

Our team utilized a rotary Delta actuator to provide precise haptic feedback as users traced mathematical graphs or shapes. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mouse/delta-real.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Rotary Delta
</div>

I focused on the feedback rendering, conducting experiments to determine the maximum stiffness the Delta could render without instability and running user studies to identify the just noticeable differences (JND) in stiffness. 
I also optimized the line thickness rendered by the mouse to ensure clear and intuitive feedback. 
The initial prototype, integrated with a modified commercial mouse and a custom GUI, received enthusiastic feedback from visually impaired users and educators, who recognized its potential educational benefits. 

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mouse/gui.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Graphical User Interface for Rendering a Circle
</div>

This device is being further developed at the [Social Haptics Robotics and Education Laboratory](https://www.ri.cmu.edu/robotics-groups/shred-lab/) at CMU. 

To learn more about this project, please see the final paper.

<div class="post">
    <header class="post-header">
      <h1 class="post-title">
        Haptic Mouse Final Paper
          <a
            href="/assets/pdf/16880_Haptics_Paper.pdf"
            target="_blank"
            rel="noopener noreferrer"
            class="float-right"
            ><i class="fa-solid fa-file-pdf"></i
          ></a>
      </h1>
    </header>
</div>