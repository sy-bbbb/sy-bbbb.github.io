---
layout: page
title: Effects of coordinate system and position of AR notification while walking (Springer VR ’23)
# description: Hybrid user interfaces that use smartphones as supplementary displays to enhance reading in AR
img: assets/img/springer23_condition.jpg
importance: 3
category: work
---

This work investigates how to effectively place AR notifications while a user is walking

<details><summary><h2>Abstract</h2></summary>
    Augmented reality (AR) head-mounted displays (HMDs) allow users to easily receive notifications while participating other tasks by projecting information directly in their field of view. Although HMDs offer such benefits in displaying notifications, there is insufficient research on the effective placement of AR notifications when the user is walking. For this, we conducted two studies based on different types of AR information to identify how the users perceive and understand the AR notifications according to placement while walking. We compared two different coordinate systems (<i>display-fixed</i> and <i>body-fixed</i>) and three different positions (<i>top</i>, <i>right</i>, and <i>bottom</i>) for icon-type and text-type notifications. The results indicated that using a <i>display-fixed</i> coordinate system for icon-type notifications yields significantly higher noticeability and comprehension. In contrast, using a <i>body-fixed</i> coordinate system for text-type notifications significantly improved comprehension and walking performance. Regarding the position of notifications, the <i>bottom</i> position resulted in a significantly higher noticeability and comprehension for both icon- and text-type notifications compared to the *top*. Based on these results, we draw some recommendations for the future design of notifications in AR HMDs.
</details>


## Research Questions

RQ1. How do the coordinate system and position of the notification affect the users’ notification experience?  
RQ2. How do the coordinate system and position of the notification affect the users’ walking experience?  
RQ3. What design recommendations can we draw from this, and what features should we consider for designing AR notifications?

## Study Design

#### Study Conditions

We used a 2 × 3 within-subjects design with two independent variables: two coordinate systems (_display-fixed_ and _body-fixed_), and three positions (_top_, _right_, and _bottom_).

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/springer23_condition2.jpg" title="position" class="img-fluid rounded z-depth-1" %}
        {% include figure.html path="assets/img/springer23_condition.jpg" title="coordinate" class="img-fluid rounded z-depth-1" %}
    </div>
</div> -->  

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/springer23_condition2.jpg" title="position" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/springer23_condition.jpg" title="coordinate" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### Experimental Task

Participants walked a track while receiving AR notifications via headset. The task was conducted with both **icon-** and **text-**based notifications, and _noticeability_, _comprehension_, _walking performance_, and _subjective ratings_ were measured for each.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/springer23_task.jpg" title="study task" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/springer23_stimuli.jpg" title="stimuli" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The top image shows the walking path used in the study. The bottom image displays the stimuli: <b>icon-type</b> (left) and <b>text-type</b> (right).
</div>

## Results

Displaying **icon-type** notifications in a _display-fixed_ coordinate system significantly increased both noticeability and comprehension.
For **text-type** notifications, a _body-fixed_ coordinate system significantly improved comprehension and walking performance.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/springer23_noticeability.jpg" title="study results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Regardless of notification type, a _bottom_ display position resulted in significantly higher noticeability and comprehension compared to a top position.
