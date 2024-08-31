---
layout: page
title: Can DNNs reflect scene typicality?
description:
img: assets/img/good_beach.png
importance: 1
category: work
related_publications: false
---

# Goal

<span style="font-size:24px">
This project aims to test whether the information extracted from deep neural networks (DNNs) can reflect human scene typicality. Similar to the project [What Makes a Good Scene Good Using DNNs?](https://pei-ling2024.github.io/projects/1_project/), this project investigates the category information extracted from DNNs but focuses on scene typicality.
</span>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/good_beach.png" title="good beach" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bad_beach.png" title="bad beach" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<span style="font-size:20px">
The beach on the left or upper is more typical than the beach on the right or lower. Both beaches were generated using DALL-E.
</div>

<hr style="height:2px;background:grey">

# Background

<span style="font-size:24px">
Typicality is a prominent property in human category literature. Typicality is a property showing that members in the same category are not equally representive to the category. Therefore, whether the representations of DNNs can reflect typicality could serve as a first test of whether DNNs capture similar information as human visual system.
</span>

<hr style="height:2px;background:grey">

# Method

<span style="font-size:24px">
We first extracted the layer activations from DNNs. Here, we chose PlaceNet, which is a CNN model that has the same archeteture as AlexNet but trained on scenes. 
A one-exemplar training SVM method is used to determine the contribution of each image. That is, one image was trained per category at a time. 
</span>

<hr style="height:2px;background:grey">

# Results

<span style="font-size:24px">
Results showed that the CNN model that we tested can capture human typicality rating in all the layers, including the first. 
</span>
