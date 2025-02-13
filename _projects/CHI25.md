---
layout: page
title: AReading with Smartphones:Understanding the Trade-offs between Enhanced Legibility and Display Switching Costs in Hybrid AR Interfaces (CHI '25)
# description: Hybrid user interfaces that use smartphones as supplementary displays to enhance reading in AR
img: assets/img/chi25_guideline.png
importance: 1
category: research
---

This work explores the trade-offs of using smartphones as supplementary displays for reading on AR head-mounted displays

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chi25_guideline.png" title="design guideline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

<details><summary>Abstract</summary>
    This research investigates the use of <b>hybrid user interfaces</b> to enhance text readability in augmented reality (AR) by combining optical see-through head-mounted displays with smartphones. While this integration can improve information legibility, it may also introduce display switching side effects. The extent to which these side effects hinder user experience and when the benefits outweigh drawbacks remain unclear. To address this gap, we conducted an empirical study (N=24) to evaluate how hybrid user interfaces affect AR reading tasks across different content distances, which induce varying levels of display switching. Our findings show that <i>hybrid user interfaces</i> offer significant readability benefits compared to using the <i>HMD only</i>, reducing mental and physical demands when reading text linked to content at closer distances. However, as the distance between displays increases, the compensatory behaviors users adopt to manage increased switching costs negate these benefits, making <i>hybrid user interfaces</i> less effective. Based on these findings, we suggest (1) using smartphones as supplementary displays for text in reading-intensive tasks, (2) implementing adaptive display positioning to minimize switching overhead in such scenarios, and (3) adjusting the smartphone's role based on content distance for less intensive reading tasks. These insights provide guidance for optimizing smartphone integration in hybrid interfaces and enhancing AR systems for reading applications. 
</details>
---

## Research Questions

RQ1. How does task performance differ between a _hybrid user interface_ and an _HMD-only_ setup across varying virtual content distances?  
RQ2. How do perceived workload factors differ between a _hybrid user interface_ and an _HMD-only_ setup across varying virtual content distances?  
RQ3. How do users’ viewing behaviors differ between a _hybrid user interface_ and an _HMD-only_ setup across varying virtual content distances?  
<br>

## Study Design

#### Study Conditions

A 2 × 4 within-subjects factorial design was employed, with **interface mode** (_HMD only_, _hybrid_) and **AR content distance** (_0.45 m_, _1 m_, _2 m_, _5 m_) as independent variables. The AR content distance levels were selected to align with Edward T. Hall’s proxemic zones.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chi25_conditions.jpg" title="study conditions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### Experimental Task

An image-text comparison task was employed to evaluate the relationship between enhanced legibility and display switching costs associated with smartphone integration. Participants compared an image presented on the left side of the HMD with a corresponding text description, which appeared either on the right side of the HMD or on a smartphone, depending on the experimental condition. The task required participants to identify the number of incorrect text descriptions. _Task performance_, _perceived workload and fatigue_, and _viewing behavior_ were measured.
<br>


## Results

Our findings show that _hybrid user interfaces_ offer significant readability benefits compared to using the _HMD only_, reducing mental and physical demands when reading text linked to content at closer distances.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chi25_subjective.jpg" title="subjective results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

However, as the distance between displays increases, the compensatory behaviors users adopt to manage increased switching costs negate these benefits, making _hybrid user interfaces_ less effective.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chi25_behaviour.jpg" title="behavioural patterns" class="img-fluid rounded z-depth-1" %}
    </div>
</div>  
<br>

## Supplementary Materials
* [Experiment Slides](/assets/pdf/chi25-slides.pdf)
* [Experiment Materials](/assets/pdf/chi25-materials.pdf)
<br>

## Git Repository
* [https://github.com/kaist-uvr-lab/HybridInterfaceStudy](https://github.com/kaist-uvr-lab/HybridInterfaceStudy)