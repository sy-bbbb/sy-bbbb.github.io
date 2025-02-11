---
layout: page
title: Integrating Smartphone Displays with OST HMDs
description: Hybrid user interfaces that use smartphones as supplementary displays to enhance reading in AR
img: assets/img/vr23_task.png
importance: 1
category: work
---

###Enhancing the Reading Experience on AR HMDs by Using Smartphones as Assistive Displays (VR '23)

The reading experience on current augmented reality (AR) head mounted displays (HMDs) is often impeded by the devices' low perceived resolution, translucency, and small field of view, especially in situations involving lengthy text. Although many researchers have proposed methods to resolve this issue, the inherent characteristics prevent these displays from delivering a readability on par with that of more traditional displays. As a solution, we explore the use of smartphones as assistive displays to AR HMDs. To validate the feasibility of our approach, we conducted a user study in which we compared a smartphone-assisted \textit{hybrid} interface against using the \textit{HMD only} for two different text lengths. The results demonstrate that the \textit{hybrid} interface yields a lower task load regardless of the text length, although it does not improve task performance. Furthermore, the \textit{hybrid} interface provides a better experience regarding user comfort, visual fatigue, and perceived readability. Based on these results, we claim that joining the spatial output capabilities of the HMD with the high-resolution display of the smartphone is a viable solution for improving the reading experience in AR.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vr23_conditions.png" title="study conditions" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vr23_task.png" title="study task" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vr23_rtlx.png" title="task load results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
